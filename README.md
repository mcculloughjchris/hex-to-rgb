# Hex to RGB!

This MySQL function will convert color hex codes to RGB!

## Instructions:
1. Upload hexToRgb.sql onto your web server
2. Login to MySQL and select your database
3. Import the .sql file by using "source /path-to-file/hexToRgb.sql" (replace /path-to-file/ with wherever you uploaded the file to)

## Usage
I'm not even sure how implementable this function is, but for example:
"SELECT hexToRgb('#000000')" would give you "0,0,0"
"SELECT hexToRgb('ffffff')" would give you "255,255,255"
