# Gapstars – Assessment (PHP /Angular) Tree Facets

[![Coverage Status](https://coveralls.io/repos/github/slimphp/Slim-Skeleton/badge.svg?branch=master)](https://coveralls.io/github/slimphp/Slim-Skeleton?branch=master)

## System requirements 
* PHP >= 7.1.3
* mysql >= 8.0
* `composer` installed 
* `git`  installed

## Install the Application

You should start by cloning the repository into your local machine.

```bash
git clone https://github.com/sali141/gapstars-facet-api.git 
cd  gapstars-facet-api
```
### Setup database
Create new database in mysql. 
```bash
CREATE DATABASE `facets`;
```

Find database dump file under `gapstars-facet-api/db/facets_categories.sql` 

Import dump to the database 

```bash
mysql -u username -p facets <  facets_categories.sql
```

Open below php file and update your mysql root password
`gapstars-facet-api/app/settings.php` 

```bash
line# 26 → 'password' => 'xxxx',
```

### Install dependencies

go to folder `gapstars-facet-api`

```bash
cd gapstars-facet-api
```

run below command
```bash
composer install
```