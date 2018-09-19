# TITLE_date_HansardGallery
A project aggregating and dispersing data from the exhibition history of the John Hansard Gallery, Southampton, UK.
http://www.hansardgallery.org.uk/
The repository is a module of the artwork Unconsumable Global Luxury Dispersion by Walter van Rijn.
Exhibition: Time After Time at John Hansard Gallery, UK. 8 September - 3 November 2018.

The data is pulled from a relational database and saved as separate tables.
1. Exhibition
2. Art
3. Artist

The Exhibition table: _ExhID, Exhibition year, DATE FROM, DATE TILL, EXHIBITION_TITLE, ARTIST, ARTIST_ID, ORGANISATIONAL INFO, Artwork_ID
Complete till 2016. Data from later exhibitions is not complete.

The Art table: 
_ArtID, _ArtistID, ARTIST_MAKER_AUTHOR, ART_title, DATE_text, DETAILS_label, _ExhID, EXHIBITION_Title.

The Artist table:
_ArtistID, ARTIST_nameonlabel, Artist_Last_First, ArtistNameFirst, ArtistNameLast, Artist_yearofbirth, Artist_countryofbirth, Artist_country, Artist_gender, Artist_website, Artist_Bio.
The names are complete but other data, from Year of Birth to Artist Bio, are not entered because of time restrains.
