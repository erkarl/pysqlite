# pysqlite 2.6.3
Clone from pysqlite 2.6.3.

## Why
In order to speed up testing in Django I wanted to use SQLite3+Spatialite as my geospatial database. However, the default for pysqlite is to build without extension loading support.

## Usage
Add to your `requirements.txt`
```console
-e git://github.com/erkarl/pysqlite.git@259e26a653b52a108dc8f1746a062e6e2b9ca714#egg=pysqlite
```
