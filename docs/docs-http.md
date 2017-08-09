# 



## Base URL

The Base URL for this API is `http://faxafloi.stsci.edu:4547/soap/`






# <a name="api_reference"></a>API Reference

* [ADEC_MAST_Binding](#adec_mast_binding)

## <a name="adec_mast_binding"></a>![Endpoint Group: ](https://apidocs.io/img/class.png "ADEC_MAST_Binding") ADEC_MAST_Binding


### <a name="do_get_summary"></a>![Endpoint: ](https://apidocs.io/img/method.png "doGetSummary") doGetSummary


**`POST`** `/doGetSummary`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description



#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| `dogetsummary` |  ``` Required ```  | TODO: Add a parameter description | 

 Example 
``` 
{
  "ra": 219.296295386411,
  "dec": 219.296295386411,
  "radius": 219.296295386411
}
``` 

#### Responses
**200** 

Body (_doGetSummaryResponse_) 
```
{
  "return": "return"
}
```


[Back to API Reference](#api_reference)

