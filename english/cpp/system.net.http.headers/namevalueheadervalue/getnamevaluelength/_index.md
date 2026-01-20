---
title: System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength method
linktitle: GetNameValueLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength method. Converts a passed string from the specified index to an instance of the NameValueHeaderValue class in C++.'
type: docs
weight: 900
url: /cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [NameValueHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| nameValueCreator | HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\> | A function that is used to create new instances of the [NameValueHeaderValue](../) class. |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

Returns the length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [NameValueHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

Returns the length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
