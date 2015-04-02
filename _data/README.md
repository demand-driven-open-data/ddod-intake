# Directory Contents

## Data dictionaries
This directory contains machine readable data dictionaries

* JSON Table Schema: http://dataprotocols.org/json-table-schema/

    ```
    {
      # fields is an ordered list of field descriptors
      # one for each field (column) in the table
      "fields": [
        # a field-descriptor
        {
          "name": "name of field (e.g. column name)",
          "title": "A nicer human readable label or title for the field",
          "type": "A string specifying the type",
          "format": "A string specifying a format",
          "description": "A description for the field"
          ...
        },
        ... more field descriptors
      ],
      # (optional) specification of the primary key
      "primaryKey": ...
      # (optional) specification of the foreign keys
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
