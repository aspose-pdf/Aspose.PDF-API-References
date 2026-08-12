---
title: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength‑metod"
linktitle: "GetNameValueListLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength‑metod. Konverterar en given sträng från det angivna indexet till en samling av instanser av klassen NameValueHeaderValue och returnerar längden på en parsad delsträng i C++."
type: docs
weight: 1000
url: /sv/cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength method


Konverterar en given sträng från det angivna indexet till samlingen av NameValueHeaderValue-klassens instanser och returnerar längden på den analyserade delsträngen.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | String | En sträng att analysera. |
| startIndex | int32_t | En startposition för analys. |
| avgränsare | char16_t | En sträng som används för att avgränsa objekt i den angivna strängen. |
| nameValueCollection | System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\> | Utdata‑parametern där en parsad samling kommer att tilldelas. |

### ReturnValue

Längden på en parsad delsträng.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
