---
title: Allocations
layout: reference
reference-type: swagger
---
##Allocations
{% swagger /api-explorer/v3-0/Allocations.swagger2.json %}

###GET Expense Allocations
This endpoint allows users to get all allocations per entry or request.

#####Parameters

Parameter | Value | Description | Parameter Type | Data Type
--------- | ----- | ----------- | -------------- | ---------
limit | numerical | The number of records to return. The default maximum is 25 and the maxuimum is 100 | query | integer
offset | | The starting point of the next set of results, after the limit specified in the limit field has been reached. | query | string
reportID | | The unique identifier for the report as it appears in the Concur Expense UI. Format: A variable-length string. Maximum length: 32 characters. | query | string
entryID | | The unique identifier for the expense entry. | query | string
itemizationID | | The unique identifier for the expense itemization. | query | string |
user | The login of the user who owns the allocation. | The login ID of the user who owns the allocation. The user must have the Web Services Admin role to use this parameter. | query | string

#####Request URL
```
https://www.concursolutions.com/api/v3.0/expense/allocations?user=<userID>
```
#####XML Example of a successful response

```
{
  "Items": [
    {
      "EntryID": "gWidFO7ikXSy7gHnNngC12jkL7khMiREv4g",
      "Percentage": "100.00000000",
      "IsPercentEdited": false,
      "IsHidden": true,
      "AccountCode1": "1",
      "AccountCode2": null,
      "Custom1": null,
      "Custom2": null,
      "Custom3": null,
      "Custom4": null,
      "Custom5": null,
      "Custom6": null,
      "Custom7": null,
      "Custom8": null,
      "Custom9": null,
      "Custom10": null,
      "Custom11": null,
      "Custom12": null,
      "Custom13": null,
      "Custom14": null,
      "Custom15": null,
      "Custom16": null,
      "Custom17": null,
      "Custom18": null,
      "Custom19": null,
      "Custom20": null,
      "ID": "gWmudeHM8AuFikny3Hrpz$s2gaNvc0E7Xfyw",
      "URI": "https://www.concursolutions.com/api/v3.0/expense/allocations/gWmudeHM8AuFikny3Hrpz$s2gaNvc0E7Xfyw"
    },
    {
      "EntryID": "gWidFO7ikXSy41$smPkwdC5cL1aku$pSgc$p4g",
      "Percentage": "100.00000000",
      "IsPercentEdited": false,
      "IsHidden": true,
      "AccountCode1": "1",
      "AccountCode2": null,
      "Custom1": null,
      "Custom2": null,
      "Custom3": null,
      "Custom4": null,
      "Custom5": null,
      "Custom6": null,
      "Custom7": null,
      "Custom8": null,
      "Custom9": null,
      "Custom10": null,
      "Custom11": null,
      "Custom12": null,
      "Custom13": null,
      "Custom14": null,
      "Custom15": null,
      "Custom16": null,
      "Custom17": null,
      "Custom18": null,
      "Custom19": null,
      "Custom20": null,
      "ID": "gWmudeHM8AuFhxez1E72ExJPksvTH0KPPyw",
      "URI": "https://www.concursolutions.com/api/v3.0/expense/allocations/gWmudeHM8AuFhxez1E72ExJPksvTH0KPPyw"
    }
  ```
###GET Expense Allocations by ID
  
This endpoint allows users to get a single allocation by ID
    
#####Parameters
Parameter | Value | Description | Parameter Type | Data Type
--------- | ----- | ----------- | -------------- | ---------
id | required | The unique identifier for the allocation. | path | string
user | Login of the user who owns the allocation. | The login ID of the user who owns the allocation. The user must have the Web Services Admin role to use this parameter. | query | string
    
#####Request URL
  
```
https://www.concursolutions.com/api/v3.0/expense/allocations?/user=<userID>/<allocationownerlogin>
```

#####XML example of a successful response

```
json placeholder
    
```
    





