---
title: System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength method
linktitle: GetEntityTagLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength method. Converts a passed string from the specified index to an instance of the EntityTagHeaderValue class in C++.'
type: docs
weight: 800
url: /cpp/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength method


Converts a passed string from the specified index to an instance of the [EntityTagHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | System::SharedPtr\<EntityTagHeaderValue\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

The length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EntityTagHeaderValue](../)
* Class [EntityTagHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
