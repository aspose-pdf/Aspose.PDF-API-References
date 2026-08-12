---
title: "Aspose::Pdf::CollectionItem klass"
linktitle: "CollectionItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionItem-klass. Representerar en samlingsobjektklass. Samlingsobjektet innehåller data som beskrivs av samlingsschemat i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.pdf/collectionitem/
---
## CollectionItem class


Representerar en samlingsobjektklass. Samlingsobjektet innehåller de data som beskrivs av samlingsschemat.

```cpp
class CollectionItem : public System::Object
```

## Nested classes

* Class [Value](./value/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AllNames](./get_allnames/)() | Hämtar en samling av alla namn på samlingsobjektvärden. |
| [get_IsEmpty](./get_isempty/)() | Hämtar ett värde som indikerar om samlingsobjektet är tomt. |
| [HasName](./hasname/)(const System::String\&) | Kontrollerar om det angivna namnet finns i samlingsobjektet. |
| [TryGetDateTimeValue](./trygetdatetimevalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\&) | Försöker hämta värdet av typen DateTime från samlingsobjektet med det angivna namnet. |
| [TryGetDoubleValue](./trygetdoublevalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<double\>\>\&) | Försöker hämta dubbelvärdet för det angivna namnet från samlingsobjektet. |
| [TryGetIntValue](./trygetintvalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\&) | Försöker hämta heltalsvärdet för ett angivet namn från samlingsobjektet. |
| [TryGetTextValue](./trygettextvalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<System::String\>\>\&) | Försöker hämta textvärdet med det angivna namnet från samlingsobjektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
