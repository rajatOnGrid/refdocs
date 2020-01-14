### Definitions

**Record**
OnGrid-References APIs are used to read/write/update records.

**Schema Code**
Each record is associated with one and only one schema code. As of now OnGrid-References supports two types of records - reference record and emploment record. Employment record is dentodated by schema code **EMP** and reference records is denoted by schema code **REF**.

Schema code is used to validate record against certain JSON schema.
- JSON schema for EMP can be found [here](https://stoplight.io/p/docs/gh/rajatongrid/refdocs/models/employment-schema.json?group=master "here").
- JSON schema for REF can be found [here](https://stoplight.io/p/docs/gh/rajatongrid/refdocs/models/reference-schema.json?group=master "here").