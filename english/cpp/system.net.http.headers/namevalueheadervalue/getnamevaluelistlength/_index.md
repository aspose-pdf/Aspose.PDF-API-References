---
title: System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength method
linktitle: GetNameValueListLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength method. Converts a passed string from the specified index to the collection of the NameValueHeaderValue-class instances and returns the length of a parsed substring in C++.'
type: docs
weight: 1000
url: /cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength method


Converts a passed string from the specified index to the collection of the NameValueHeaderValue-class instances and returns the length of a parsed substring.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to analyze. |
| startIndex | int32_t | A start position for analyzing. |
| delimiter | char16_t | A string that is used to delimit items in the specified string. |
| nameValueCollection | System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\> | The output parameter where a parsed collection will be assigned. |

### ReturnValue

The length of a parsed substring.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
