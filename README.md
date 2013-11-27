# pysqlite 2.6.3
Clone from pysqlite 2.6.3.

## Why
In order to speed up testing in Django I wanted to use SQLite3+Spatialite as my geospatial database. However, the default for pysqlite is to build without extension loading support.

## Usage
Add to your `requirements.txt`
```console
-e git://github.com/erkarl/pysqlite.git@704ea34d3a9b783b1b67e8d65299a288ce50fb8a#egg=pysqlite
```
