World Flags
===========

This is a sprite file of the world's flags alonng with the CSS file to render them.

The countries are listed in alphabetical order by country name.
Countries can be target via CSS by uisng .flag-XXX where XXX represents the ISO 3166-1 alpha-3 standard for that country.

Note, that some countries have been commented out, either a flag does not exist for them, or I haven't been able to identify the correct flag for that country. You are welcome to update this CSS or images file and submit a pull request.

Updating
--------
The CSS follows the following pattern:
    .flag-AGO {background-position: calc( ( _X_ * 7.23%) + 3px) calc( ( _Y_ * 7.20%) + 1px);}

Where _X_ and _Y_ represents the position of the flag starting from the upper left hand corner. The first flag would be 0,0. 
