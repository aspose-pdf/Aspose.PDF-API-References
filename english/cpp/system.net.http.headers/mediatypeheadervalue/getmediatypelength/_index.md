---
title: System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength method
linktitle: GetMediaTypeLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength method. Converts a passed string from the specified index to an instance of the MediaTypeHeaderValue class in C++.'
type: docs
weight: 1000
url: /cpp/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength method


Converts a passed string from the specified index to an instance of the [MediaTypeHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| mediaTypeCreator | HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\> | The delegate that is used to create instances of the [MediaTypeHeaderValue](../) class. |
| parsedValue | System::SharedPtr\<MediaTypeHeaderValue\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

Returns the length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MediaTypeHeaderValue](../)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
