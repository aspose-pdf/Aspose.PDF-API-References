---
title: "Aspose::Pdf::CollectionItem::TryGetTextValue-metod"
linktitle: "TryGetTextValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionItem::TryGetTextValue-metod. Försöker hämta textvärdet med det angivna namnet från samlingsobjektet i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf/collectionitem/trygettextvalue/
---
## CollectionItem::TryGetTextValue method


Försöker hämta textvärdet med det angivna namnet från samlingsobjektet.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetTextValue(const System::String &name, System::SharedPtr<CollectionItem::Value<System::String>> &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const System::String\& | Namnet på textvärdet. |
| värde | System::SharedPtr\<CollectionItem::Value\<System::String\>\>\& | När den här metoden returnerar, innehåller den textvärdet som är associerat med det angivna namnet, om namnet hittas; annars null. |

### ReturnValue

true om textvärdet med det angivna namnet hittas; annars false.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
