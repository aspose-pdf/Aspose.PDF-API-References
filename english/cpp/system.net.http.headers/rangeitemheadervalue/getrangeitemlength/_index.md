---
title: System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength method
linktitle: GetRangeItemLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength method. Converts a passed string from the specified index to an instance of the RangeItemHeaderValue class in C++.'
type: docs
weight: 700
url: /cpp/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength method


Converts a passed string from the specified index to an instance of the [RangeItemHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | System::SharedPtr\<RangeItemHeaderValue\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

Returns the length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RangeItemHeaderValue](../)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
