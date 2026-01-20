---
title: System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength method
linktitle: GetContentRangeLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength method. Converts a passed string from the specified position to an instance of the ContentRangeHeaderValue class in C++.'
type: docs
weight: 1200
url: /cpp/system.net.http.headers/contentrangeheadervalue/getcontentrangelength/
---
## ContentRangeHeaderValue::GetContentRangeLength method


Converts a passed string from the specified position to an instance of the [ContentRangeHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | System::SharedPtr\<Object\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

The length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ContentRangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
