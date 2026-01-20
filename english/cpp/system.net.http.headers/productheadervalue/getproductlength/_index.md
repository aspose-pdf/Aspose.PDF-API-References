---
title: System::Net::Http::Headers::ProductHeaderValue::GetProductLength method
linktitle: GetProductLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ProductHeaderValue::GetProductLength method. Converts a passed string from the specified index to an instance of the ProductHeaderValue class in C++.'
type: docs
weight: 700
url: /cpp/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength method


Converts a passed string from the specified index to an instance of the [ProductHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | System::SharedPtr\<ProductHeaderValue\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

Returns the length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ProductHeaderValue](../)
* Class [ProductHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
