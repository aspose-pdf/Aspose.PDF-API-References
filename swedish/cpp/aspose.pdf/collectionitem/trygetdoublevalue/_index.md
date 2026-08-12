---
title: "Aspose::Pdf::CollectionItem::TryGetDoubleValue method"
linktitle: "TryGetDoubleValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionItem::TryGetDoubleValue method. Försöker hämta dubbelvärdet för det angivna namnet från samlingsobjektet i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf/collectionitem/trygetdoublevalue/
---
## CollectionItem::TryGetDoubleValue method


Försöker hämta dubbelvärdet för det angivna namnet från samlingsobjektet.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetDoubleValue(const System::String &name, System::SharedPtr<CollectionItem::Value<double>> &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const System::String\& | Namnet på värdet som ska hämtas. |
| värde | System::SharedPtr\<CollectionItem::Value\<double\>\>\& | När den här metoden returnerar, innehåller den dubbelvärdet som är associerat med det angivna namnet, om namnet hittas; annars null. Denna parameter skickas oinitierad. |

### ReturnValue

true om värdet hämtas framgångsrikt; annars false.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
