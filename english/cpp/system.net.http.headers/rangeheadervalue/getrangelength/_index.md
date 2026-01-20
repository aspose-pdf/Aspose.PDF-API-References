---
title: System::Net::Http::Headers::RangeHeaderValue::GetRangeLength method
linktitle: GetRangeLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::RangeHeaderValue::GetRangeLength method. Converts a passed string from the specified index to an instance of the RangeHeaderValue class in C++.'
type: docs
weight: 800
url: /cpp/system.net.http.headers/rangeheadervalue/getrangelength/
---
## RangeHeaderValue::GetRangeLength method


Converts a passed string from the specified index to an instance of the [RangeHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::RangeHeaderValue::GetRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | System::SharedPtr\<Object\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

Returns the length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
