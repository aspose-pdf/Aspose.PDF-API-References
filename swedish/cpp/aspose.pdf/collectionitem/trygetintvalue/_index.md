---
title: "Aspose::Pdf::CollectionItem::TryGetIntValue method"
linktitle: "TryGetIntValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionItem::TryGetIntValue method. Försöker hämta heltalsvärdet för ett angivet namn från samlingsobjektet i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf/collectionitem/trygetintvalue/
---
## CollectionItem::TryGetIntValue method


Försöker hämta heltalsvärdet för ett angivet namn från samlingsobjektet.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetIntValue(const System::String &name, System::SharedPtr<CollectionItem::Value<int32_t>> &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const System::String\& | Namnet på värdet som ska hämtas. |
| värde | System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\& | När den här metoden returnerar, innehåller den värdet som är associerat med det angivna namnet, om namnet hittas; annars null. |

### ReturnValue

true om värdet som är associerat med det angivna namnet hittas; annars false.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
