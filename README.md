<h3 align="center">
    <a href="https://rene-poepperl.de">
        <img src="https://rene-poepperl.de/wp-content/uploads/2023/01/po%CC%88pperl-code-content.png" />
    </a>
</h3>

Country List
============

List of all countries with names and ISO 3166-1 codes in all languages and data 
formats. This repo is a fork from the original umpirsky/country-list package. 
It makes the project easier to use in PHP projects.
    

Install
-------------
```shell
composer require poepperl-cc/country-list
```

Formats Available
-----------------

- Text
- JSON
- YAML
- XML
- HTML
- CSV
- SQL
    * MySQL
    * PostgreSQL
    * SQLite
- PHP
- XLIFF


Multilingual
------------

All formats are also available in multiple languages, please find full language list [here](https://github.com/poepperl-cc/country-list/tree/master/data).

Build
-----

Country list is available out of the box, but if you want to submit patches, add new formats,
update data source or contribute in any other way, you will probably want to rebuild the list:

```bash
$ docker-compose run php /var/www/html/bin/build -v
```
If you need to install composer, get it from https://getcomposer.org/
installation instructions can be found here:
https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx

