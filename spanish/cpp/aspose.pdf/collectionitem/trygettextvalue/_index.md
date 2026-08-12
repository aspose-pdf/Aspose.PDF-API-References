---
title: "Método Aspose::Pdf::CollectionItem::TryGetTextValue"
linktitle: "TryGetTextValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::CollectionItem::TryGetTextValue. Intenta obtener el valor de texto con el nombre especificado del elemento de colección en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf/collectionitem/trygettextvalue/
---
## CollectionItem::TryGetTextValue method


Intenta obtener el valor de texto con el nombre especificado del elemento de la colección.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetTextValue(const System::String &name, System::SharedPtr<CollectionItem::Value<System::String>> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const System::String\& | El nombre del valor de texto. |
| valor | System::SharedPtr\<CollectionItem::Value\<System::String\>\>\& | Cuando este método devuelve, contiene el valor de texto asociado con el nombre especificado, si se encuentra el nombre; de lo contrario, null. |

### ReturnValue

true si se encuentra el valor de texto con el nombre especificado; de lo contrario, false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
