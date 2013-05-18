gdal2tiles
==========

Modified gdal2tiles that will only produce tiles that are completely full of
imagery. This eliminates tiles with nodata borders, which if you're working
with jpg tiles can make mixing tilesets difficult.

