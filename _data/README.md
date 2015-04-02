# Contents

This directory contains machine readable data catalogs

* JSON Table Schema: http://dataprotocols.org/json-table-schema/

``` html
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