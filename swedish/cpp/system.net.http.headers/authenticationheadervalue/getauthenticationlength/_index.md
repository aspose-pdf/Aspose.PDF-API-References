---
title: "System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength metod"
linktitle: "GetAuthenticationLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength metod. Tolkar den angivna strängen och returnerar det sista indexet för strängrepresentationen i C++."
type: docs
weight: 800
url: /sv/cpp/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength method


Analyserar den angivna strängen och returnerar det sista indexet för strängrepresentationen.

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | String | Strängen som måste analyseras. |
| startIndex | int32_t | En startposition för parsning. |
| parsedValue | System::SharedPtr\<Object\>\& | Utdata-parametern där ett analyserat värde kommer att tilldelas. |

### ReturnValue

Längden på en analyserad delsträng, annars 0.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [AuthenticationHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
