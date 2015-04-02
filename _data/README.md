# Directory Contents

## Data dictionaries
This directory contains machine readable data dictionaries.  Multiple formats are possible, including: SQL DDL, XML, JSON, YAML

* ANSI SQL Standard 
   - DDL (Data Definition Language): "CREATE TABLE"
   - [SQL/Schemata](http://webstore.ansi.org/RecordDetail.aspx?sku=ISO%2FIEC+9075-11%3A2011)
 
        ```
        testdb-# \d company
                    Table "public.company"
          Column   |     Type      | Modifiers
        -----------+---------------+-----------
         id        | integer       | not null
         name      | text          | not null
         address   | character(50) |
         join_date | date          |
        Indexes:
            "company_pkey" PRIMARY KEY, btree (id)
        ```

* JSON Table Schema: http://dataprotocols.org/json-table-schema/

    ```
    "schema": {
      "fields": [
        {
          "name": "name of field (e.g. column name)",
          "title": "A nicer human readable label or title for the field",
          "type": "A string specifying the type",
        },
        ... more field descriptors
      ],
      "primaryKey": ...
      "foreignKeys": ...
    }
    ```

* YAML schema files used for Doctrine ORM: http://doctrine.readthedocs.org/en/latest/en/manual/yaml-schema-files.html

* XML schema syntax for Google's DSPL (Dataset Publishing Language): https://developers.google.com/public-data/docs/schema/dspl9

* W3 XML Schema: http://www.w3.org/TR/xmlschema-2/#built-in-primitive-datatypes


## CSV storage formats
* Open Knowledge Data Packager - CKAN Extension http://ckan.org/2014/06/09/the-open-knowledge-data-packager/

* Tabular Data Package Spec: http://dataprotocols.org/tabular-data-package/

* The above two are also part of a W3C standards track:
www.w3.org/TR/tabular-data-model/<http://www.w3.org/TR/tabular-data-model/>
