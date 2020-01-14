### Definitions

# eLocker

![](https://media.glassdoor.com/sqll/2119869/ongrid-india-squarelogo-1561035387986.png)

![](https://img.shields.io/github/release/pandao/editor.md.svg)



### Get Started

##### Overview

- eLocker is a secure and digital repository of information “written” by organizations in such a manner that the “writing” process guarantees authenticity.

- This information gets consumed by other organizations via a ‘reading” process. That organizations that “read” may typically be employers or service providers. 

- An example of such information is employment records. When it comes to “reading” information about an individual, it is usually allowed with consent of the individual to ensure privacy and related regulatory compliance.   

- An example of such information is “employment records” written by ex-employers and read by new employers. eLocker thus helps in increasing the efficiency of the employee verification process. 


##### OnGrid-References APIs provide 4 main APIs.

- Read
- Write
- Update
- Search

##### Get API Credentials

- Get your Client id, Client Secret & Encryption Key from Ongrid

|  API Credentials | Description |
| ------------ |  ------------- |
|  Client Id |  Description |
|  Client Secret |  Description |
|  Encryption Key |  Description |


**Schema Code**

Each record is associated with one and only one schema code. As of now OnGrid-References supports two types of records - reference record and emploment record. Employment record is dentodated by schema code **EMP** and reference records is denoted by schema code **REF**.

Schema code is used to validate record against certain JSON schema.
- JSON schema for EMP can be found [here](https://stoplight.io/p/docs/gh/rajatongrid/refdocs/models/employment-schema.json?group=master "here").
- JSON schema for REF can be found [here](https://stoplight.io/p/docs/gh/rajatongrid/refdocs/models/reference-schema.json?group=master "here").