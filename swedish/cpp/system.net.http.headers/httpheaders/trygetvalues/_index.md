---
title: "System::Net::Http::Headers::HttpHeaders::TryGetValues-metod"
linktitle: "TryGetValues"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::HttpHeaders::TryGetValues-metoden. Försöker hämta motsvarande värden med det angivna namnet i C++."
type: docs
weight: 1900
url: /sv/cpp/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues method


Försöker hämta motsvarande värden för det angivna namnet.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Headernamnet. |
| värden | System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | En instans där motsvarande värden kommer att tilldelas. |

### ReturnValue

Sant när rubrikvärdena hittas med det angivna namnet, annars falskt.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
