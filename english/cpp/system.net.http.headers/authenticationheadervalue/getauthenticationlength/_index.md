---
title: System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength method
linktitle: GetAuthenticationLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength method. Parses the specified string and returns the last index of the string representation in C++.'
type: docs
weight: 800
url: /cpp/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength method


Parses the specified string and returns the last index of the string representation.

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | The string that must be parsed. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | System::SharedPtr\<Object\>\& | The output parameter where a parsed value will be assigned. |

### ReturnValue

The length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [AuthenticationHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
