# 



## Base URL

The Base URL for this API is `http://faxafloi.stsci.edu:4547/soap/`









# <a name="api_reference"></a>API Reference

* [ADEC_MAST_Binding](#adec_mast_binding)

## <a name="adec_mast_binding"></a>![Endpoint Group: ](https://apidocs.io/img/class.png "ADEC_MAST_Binding") ADEC_MAST_Binding


### <a name="do_get_summary"></a>![Endpoint: ](https://apidocs.io/img/method.png "doGetSummary") doGetSummary


**`POST`** `/doGetSummary`

> doGetSummary




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [doGetSummary](#do_get_summary) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "ra": 145.051046197792,
  "dec": 145.051046197792,
  "radius": 145.051046197792
}
``` 

#### Responses
**200** 


Body ([doGetSummaryResponse](#do_get_summary_response)) 
```
{
  "return": "return"
}
```


[Back to API Reference](#api_reference)

## <a name="api_types"></a>![Models: ](https://apidocs.io/img/class.png "API Types") API Types

This section provides details on the available types. The primitive types available are:

| Type | Example |
| ---- | -------- |
| **string** | `hello world` |
| **boolean** |	`true` |
| **number** | `1` |
| **precision** | `1.5` |
| **datetime** | `2016-03-13T12:52:32.123Z` |
| **date** | `2016-03-13` |
|**void** | |
| **dynamic** | |
| **binary** | |
| **long** | `12345678910` |
| **file** | |
| **uuid** | `0f8fad5b-d9cb-469f-a165-70867728950e` |


In addition to the above types, the following complex types are also available:
### <a name="urn:adec_mast_summary_result"></a>![Model: ](https://apidocs.io/img/method.png "urn:ADEC_MAST_SummaryResult") urn:ADEC_MAST_SummaryResult



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| missionName | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| dataIdCount | [number](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="do_get_summary_response"></a>![Model: ](https://apidocs.io/img/method.png "doGetSummaryResponse") doGetSummaryResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| return | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="do_get_summary"></a>![Model: ](https://apidocs.io/img/method.png "doGetSummary") doGetSummary



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ra | [precision](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| dec | [precision](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| radius | [precision](#api_types) |  ``` Required ```  | TODO: Add a property description |

