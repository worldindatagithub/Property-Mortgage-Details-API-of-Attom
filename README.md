# Property Mortgage Details API of Attom #
The Attom property mortgage details API allows developers to retrieve information about the mortgage of a specific property using its Attom ID. This API is useful for any application that requires information about the mortgage status of a property. By utilizing this API, developers can easily access data such as the mortgage amount, lender, and payment frequency. In summary, the purpose of this API is to provide developers with a way to easily obtain mortgage details for a specific property.


[Property Mortgage Details API](https://www.worldindata.com/api/Attom-property-mortgage-details-api)

The Worldindata data marketplace offers a variety of third party APIs to users. One of the goals of this platform is to make it easier for developers to access and utilize these APIs. To achieve this, the Worldindata team works to provide clear documentation and user-friendly interfaces for the APIs on their platform. This helps developers to quickly and easily integrate the APIs into their own applications, without having to spend a lot of time learning how to use them.


## Clients, Industry, and Sectors ##

**Industry and Sectors**
- mortgage
- real-estate
- accommodation
- property listing
- and more

**Client Types**
- property listing platforms and websites
- real-estate analysts
- and more




## API Parameters, JSON output and Objects ##
The GET /property/detailmortgage endpoint is an important part of the Attom property mortgage API, allowing developers to retrieve detailed mortgage information for a specific property using its Attom ID.


**Filter Parameters**
- accept
- attomid


```
{
  "status": {
    "version": "1.0.0",
    "code": 0,
    "msg": "SuccessWithResult",
    "total": 1,
    "page": 1,
    "pagesize": 10,
    "transactionID": "e7ec4bde63013646bf89ccd6d7e56460"
  },
  "property": [
    {
      "identifier": {
        "Id": 184713191,
        "attomId": 184713191,
        "fips": "08031",
        "apn": "02192-04-018-000"
      },
      "lot": {
        "lotnum": "31,32",
        "lotsize1": 0.1076676,
        "lotsize2": 4690,
        "pooltype": "NO POOL"
      },
      "area": {
        "blockNum": "36",
        "loctype": "VIEW - NONE",
        "countrysecsubd": "Denver",
        "countyuse1": "113  ",
        "muncode": "DE",
        "munname": "DENVER",
        "srvyRange": "68W",
        "srvySection": "19",
        "srvyTownship": "03S",
        "subdname": "BERKELEY"
      },
      "address": {
        "country": "US",
        "countrySubd": "CO",
        "line1": "4529 WINONA CT",
        "line2": "DENVER, CO 80212",
        "locality": "DENVER",
        "matchCode": "ExaStr",
        "oneLine": "4529 WINONA CT, DENVER, CO 80212",
        "postal1": "80212",
        "postal2": "2512",
        "postal3": "C037"
      },
      "location": {
        "accuracy": "Rooftop",
        "latitude": "39.778926",
        "longitude": "-105.047775",
        "distance": 0,
        "geoid": "CO08031, CS0891007, DB0803360, ND0000119198, ND0004861239, PL0820000, SB0000076114, SB0000076155, SB0000076161, SB0000135819, SB0000143772, ZI80212",
        "geoIdV4": {
          "CS": "4c0507d0d7894d2d48e4e03e1c0240fc",
          "N1": "b26d02d9330761156fc0cfd4ed8bf9a1",
          "N2": "27e220314436f6edd5e606ddcd28156d",
          "PL": "7de845f7ba9b234a2c5adfca1db76c64",
          "ZI": "0149d0a55ef2d6b71071a39f4e13d6eb"
        }
      },
      "summary": {
        "absenteeInd": "ABSENTEE(MAIL AND SITUS NOT =)",
        "propclass": "Single Family Residence / Townhouse",
        "propsubtype": "Residential",
        "proptype": "SFR",
        "yearbuilt": 1900,
        "propLandUse": "SFR",
        "propIndicator": "10",
        "legal1": "BERKELEY B36 L31 & S/2 OF L32 EXC REAR 8FT TO CITY"
      },
      "utilities": {
        "heatingfuel": "GAS",
        "heatingtype": "CENTRAL"
      },
      "building": {
        "size": {
          "bldgsize": 934,
          "grosssize": 1414,
          "grosssizeadjusted": 934,
          "groundfloorsize": 934,
          "livingsize": 934,
          "sizeInd": "LIVING SQFT",
          "universalsize": 934
        },
        "rooms": {
          "bathfixtures": 5,
          "bathsfull": 1,
          "bathstotal": 1,
          "beds": 2,
          "roomsTotal": 5
        },
        "interior": {
          "bsmtsize": 478,
          "bsmttype": "UNFINISHED",
          "fplccount": 1,
          "fplcind": "Y",
          "fplctype": "YES"
        },
        "construction": {
          "condition": "GOOD",
          "wallType": "BRICK"
        },
        "parking": {
          "prkgSize": 240,
          "prkgSpaces": "1"
        },
        "summary": {
          "archStyle": "OTHER",
          "levels": 1,
          "quality": "EXCELLENT",
          "unitsCount": "1",
          "view": "VIEW - NONE",
          "yearbuilteffective": 2014
        }
      },
      "mortgage": {
        "lender": {
          "companycode": "-1"
        },
        "title": {
          "companyname": "NONE AVAILABLE"
        },
        "amount": 0,
        "date": "",
        "deedtype": "BS",
        "duedate": ""
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    }
  ]
}

```
**Objects**
- property
- identifier
- obPropId
- fips
- apn
- attomId
- lot
- area
- address
- mortgage
- lender
- companycode
- title
- companyname
- amount
- date
- deedtype
- duedate
- lastModified
- pubDate

## Software Development Kits ##
The Attom property mortgage API is supported by a range of Software Development Kits (SDKs), including Java, PHP, Ruby, Python, and JavaScript. These SDKs provide developers with an easy way to integrate the API into their applications and make use of its functionality.


### Disclaimer statement ###
Worldindata is a data marketplace that aims to connect developers with data providers and make it easier for them to access and utilize data. While we do not own the data ourselves, we are big fans of the Attom property mortgage details API and strive to make it as user-friendly as possible for our users. Please note that Worldindata is not responsible for the accuracy or reliability of the data provided through the API, and it is up to the developer to use the data in accordance with the terms of service of the data provider.


[Worldindata](https://www.worldindata.com)
