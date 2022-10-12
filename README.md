# Neighbourhood API

## Description

API working with Express JS and sending response via JSON format

<img width="1680" alt="api" src="https://user-images.githubusercontent.com/82246823/195327754-cc191aa4-832d-4e90-a31c-a046025bc6b5.png">

## Installation



## Usage

Call the API using these endpoints:

Path | HTTP Verb | Action
--- | --- | ---
/search | GET | index
/search/person/:name | GET |
/search/address/:postcode | GET |
/search/house/:houseName | GET |
/search/neighbors?age&numOfHouseHold | GET |


## Examples for response:
  It response in json format:
  1- Req: get(/search/person/:name)
     Res: {
            name: "Micheal",
            age: 23,
            numberOfHouseHold: 2,
            postcode: "2xb 11wr"
          }
          
   2- Req: get(search/address/:postcode)
      Res: {
              buildingName: "New Court",
              buildingNumber: 23,
              numberOfHousehold: 15
           }
