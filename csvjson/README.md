### Convert a csv file into a JSON file to be used in a web application

Use csvjson - part of [csvkit](https://csvkit.readthedocs.io/)

For tasks related with csv wrangling, *[csvkit](https://csvkit.readthedocs.io/en/0.9.1/index.html)* is a great tool to have in your toolbox. Created by [@onyxfish](https://twitter.com/onyxfish)

Bundled with many other interesting tools that _you definitely should check out_ comes csvjson a command line tool that does exactly what our proposed challenge needs.

By default it will output the json file as a list an element for each row in the CSV.

    $ csvjson example.csv > example.json

But we can add a key in the conversion process that will allow us to obtain an array of objects keyed by a given column (the values of this column in the CSV must be unique).

    $ csvjson -k COMBOKEY example.csv > example_by_key.json

As an extra super nice feature csvjson also added support gor geojson generation. So if we have latitude and longitude available and know the coordinate reference system of those coordinates we might as well use it for our soon to be beautiful web map

    $ csvjson --lat latitude --lon longitude --k slug --crs EPSG:4269 -i 4 examples/test_geo.csv

Apart from being an amazing and really useful library, the documentation is just as good so please dive in and use it, I promise you want regret it.

#### External links

* [Install](https://csvkit.readthedocs.io/en/0.9.1/install.html)
* [Usage](https://csvkit.readthedocs.io/en/0.9.1/scripts/csvjson.html)
