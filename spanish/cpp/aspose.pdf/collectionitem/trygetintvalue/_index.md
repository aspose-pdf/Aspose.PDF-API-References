---
title: "Aspose::Pdf::CollectionItem::TryGetIntValue método"
linktitle: "TryGetIntValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::CollectionItem::TryGetIntValue método. Intenta obtener el valor entero para un nombre especificado del elemento de colección en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf/collectionitem/trygetintvalue/
---
## CollectionItem::TryGetIntValue method


Intenta obtener el valor entero para un nombre especificado del elemento de la colección.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetIntValue(const System::String &name, System::SharedPtr<CollectionItem::Value<int32_t>> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const System::String\& | El nombre del valor a recuperar. |
| valor | System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\& | Cuando este método regresa, contiene el valor asociado con el nombre especificado, si se encuentra el nombre; de lo contrario, null. |

### ReturnValue

true si el valor asociado con el nombre especificado se encuentra; de lo contrario, false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
