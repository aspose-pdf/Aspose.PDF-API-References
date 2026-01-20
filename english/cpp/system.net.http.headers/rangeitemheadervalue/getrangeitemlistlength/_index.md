---
title: System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength method
linktitle: GetRangeItemListLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength method. Converts a passed string from the specified position to the collection of the RangeItemHeaderValue-class instances in C++.'
type: docs
weight: 800
url: /cpp/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength method


Converts a passed string from the specified position to the collection of the RangeItemHeaderValue-class instances.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| rangeCollection | System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\> | An instance where a parsed collection will be assigned. |

### ReturnValue

The length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [RangeItemHeaderValue](../)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
