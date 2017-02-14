A curated list of data wrangling resources with a bias towards pragmatic tools.


## Excel to CSV conversion

[xlsx2csv](https://github.com/dilshod/xlsx2csv)
Command line tool to convert xslx to csv. Fast and works for large xlsx files. Doesn't handle passwords.

[libreoffice](https://www.libreoffice.org/)
Use [GUI](https://www.libreoffice.org/) or [headless mode](http://shades-of-orange.com/post/How-to-Convert-an-XSLX-File-to-CSV-with-UTF-8-Encoding-Using-LibreOffice-OpenOffice) to convert xlsx to CSV. Doesn't seem to handle passwords or multiple sheets in headless mode 

[Apache POI](https://poi.apache.org/download.html)
Java APIs for manipulating various file formats based upon the Office Open XML standards. Can be used to extract text from spreadsheets, supports passwords etc. but can be memeory intensive.

[Excel Streaming Reader](https://github.com/monitorjbl/excel-streaming-reader#implementation-details)
Java streaming Excel reader using Apache POI - use for reading in large files without exhausting memory

## Data Search/Filtering
[ripgrep](https://github.com/BurntSushi/ripgrep)
Extremely fast grep alternative.

## JSON Processing
[jq](https://stedolan.github.io/jq/)
A lightweight and flexible command-line JSON processor


## XML Processing
[xmlstarlet](http://xmlstar.sourceforge.net/docs.php)
Command line tools to transform, query, validate, and edit XML documents


## CSV Processing
[XSV CSV Toolkit](https://github.com/BurntSushi/xsv)
Fast, command line toolkit for CSV manipulation and analysis. Written in RUST


## Compression Tools
[zstandard](http://facebook.github.io/zstd) 
Fast, efficient compressor for small data sets (less than 100MB) leveraging pre trained dictionaries.

[shoco](http://ed-von-schleck.github.io/shoco/#home)
A fast acii biased, entropy encoder, for short strings using trained bigrams. Trained on english by default, supports training custom models.

[smaz](https://github.com/antirez/smaz)
Dictionary based compressor for very small strings (less than 100 bytes). By default uses english dictionary but can be customized via code.


## Data Exploration and Sharing
[Redash](https://github.com/getredash/redash)
Connect to any data source, easily visualize and share your data via dashboard. Open source and self hostable.

[Superset](https://github.com/airbnb/superset)
Data exploration platform designed to be visual, intuitive, and interactive. From Airbnb, python based, supports druid alo with other SQL sources.

[Metabase](https://github.com/metabase/metabase)
Visual analytics and dashboards from a wide range of SQL sources. Java based, SQL and non SQL modes, easy to share. 


## Postal Address Processing
[libpostal](https://github.com/openvenues/libpostal)
Libpostal is an open source project designed to provide fast, global address expansion and parsing using natural language processing techniques. Unlike several open source address parsing systems which rely explicit patterns and complex regular expressions, libpostal relies on a trained model derived from a corpus of global place names, national address patterns, and different languages terminology. It was created by Al Barrentine, initially for the Mapzen OpenVenues project. See [intro post](https://medium.com/@albarrentine/statistical-nlp-on-openstreetmap-b9d573e6cc86) for details.

[pelias.io](http://pelias.io/)
A modular, open-source geocoder built on top of ElasticSearch for fast geocoding. Works with OpenStreetMap, OpenAddresses, Geonames, and Who's on First and can leverage libpostal for address parsing and expansion.


## Datasets
[Global Chain Store Names List](https://github.com/openvenues/chain_stores)
131k chain store names from OpenVenues


## Test Data Generation
Generate fake data for testing and demos

[phoney](https://github.com/yields/phony)
Command line program that accepts a template and outputs fake data. golang based.

[faker.js](https://github.com/Marak/faker.js) and [faker cli](https://github.com/lestoni/faker-cli)
Generate fake data from a browser, cli or REST call. Node.js based and includes avatars. See [demo](https://cdn.rawgit.com/Marak/faker.js/master/examples/browser/index.html)

[faker](http://faker.readthedocs.io/en/master/)
Python based module and command line tool for generating fake data

[elizabeth](https://github.com/lk-geimfari/elizabeth)
Python module for generating fake data profiles. Claims to be faster than alternatives, simpler and more self contained.

[mockeroo](http://www.mockaroo.com/)
Web app for generating realistic test data. Free up to 1000 records.

[generatedata.com](http://www.generatedata.com/)
Web app for generating test data. Generate up to 100 for free, 5000 for $20 or download from [http://benkeen.github.io/generatedata/](http://benkeen.github.io/generatedata/)

[dsgen-big](https://github.com/yipeng/dsgen-big)
Dataset generator for producing dirty data with duplicates, typos etc. Based on the origional Febrl dbgen code.
