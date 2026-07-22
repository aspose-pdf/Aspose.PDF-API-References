---
title: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength metod"
linktitle: "GetNameValueLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength metod. Konverterar en given sträng från det angivna indexet till en instans av NameValueHeaderValue-klassen i C++."
type: docs
weight: 900
url: /sv/cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) method


Konverterar en given sträng från det angivna indexet till en instans av klassen [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | String | En sträng att tolka. |
| startIndex | int32_t | En startposition för parsning. |
| nameValueCreator | HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\> | En funktion som används för att skapa nya instanser av klassen [NameValueHeaderValue](../). |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | En instans där ett parsat objekt kommer att tilldelas. |

### ReturnValue

Returnerar längden på en analyserad delsträng, annars 0.

## Se även

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) method


Konverterar en given sträng från det angivna indexet till en instans av klassen [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | String | En sträng att tolka. |
| startIndex | int32_t | En startposition för parsning. |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | En instans där ett parsat objekt kommer att tilldelas. |

### ReturnValue

Returnerar längden på en analyserad delsträng, annars 0.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
