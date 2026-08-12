---
title: "System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength method"
linktitle: "GetMediaTypeLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength method. Konverterar en given sträng från det angivna indexet till en instans av MediaTypeHeaderValue-klassen i C++."
type: docs
weight: 1000
url: /sv/cpp/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength method


Konverterar en given sträng från det angivna indexet till en instans av klassen [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | String | En sträng att tolka. |
| startIndex | int32_t | En startposition för parsning. |
| mediaTypeCreator | HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\> | Delegaten som används för att skapa instanser av klassen [MediaTypeHeaderValue](../). |
| parsedValue | System::SharedPtr\<MediaTypeHeaderValue\>\& | En instans där ett parsat objekt kommer att tilldelas. |

### ReturnValue

Returnerar längden på en analyserad delsträng, annars 0.

## Se även

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MediaTypeHeaderValue](../)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
