---
title: "Aspose::Pdf::CollectionItem::TryGetDateTimeValue method"
linktitle: "TryGetDateTimeValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionItem::TryGetDateTimeValue method. Försöker hämta värdet av typen DateTime från samlingsobjektet med det angivna namnet i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf/collectionitem/trygetdatetimevalue/
---
## CollectionItem::TryGetDateTimeValue method


Försöker hämta värdet av typen DateTime från samlingsobjektet med det angivna namnet.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetDateTimeValue(const System::String &name, System::SharedPtr<CollectionItem::Value<System::DateTime>> &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const System::String\& | Namnet på värdet som ska hämtas. |
| värde | System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\& | När den här metoden returnerar, innehåller den värdet som är associerat med det angivna namnet, om namnet hittas; annars null. Denna parameter skickas oinitierad. |

### ReturnValue

true om värdet som är associerat med det angivna namnet hämtas framgångsrikt; annars false.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [DateTime](../../../system/datetime/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
