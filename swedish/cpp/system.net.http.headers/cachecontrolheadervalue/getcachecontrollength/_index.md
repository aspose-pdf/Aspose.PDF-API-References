---
title: "System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength metod"
linktitle: "GetCacheControlLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength metod. Konverterar en given sträng från det angivna indexet till en instans av CacheControlHeaderValue-klassen i C++."
type: docs
weight: 3400
url: /sv/cpp/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength method


Konverterar en given sträng från det angivna indexet till en instans av klassen [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | String | En sträng att tolka. |
| startIndex | int32_t | En startposition för parsning. |
| storeValue | System::SharedPtr\<CacheControlHeaderValue\> | Ett värde som måste läggas till i det analyserade objektet. |
| parsedValue | System::SharedPtr\<CacheControlHeaderValue\>\& | En instans där ett parsat objekt kommer att tilldelas. |

### ReturnValue

Längden på en analyserad delsträng, annars 0.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CacheControlHeaderValue](../)
* Class [CacheControlHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
