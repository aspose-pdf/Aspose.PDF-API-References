---
title: "Método Aspose::Pdf::CollectionItem::TryGetDoubleValue"
linktitle: "TryGetDoubleValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::CollectionItem::TryGetDoubleValue. Intenta obtener el valor doble para el nombre especificado del elemento de colección en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf/collectionitem/trygetdoublevalue/
---
## CollectionItem::TryGetDoubleValue method


Intenta obtener el valor double para el nombre especificado del elemento de la colección.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetDoubleValue(const System::String &name, System::SharedPtr<CollectionItem::Value<double>> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const System::String\& | El nombre del valor a recuperar. |
| valor | System::SharedPtr\<CollectionItem::Value\<double\>\>\& | Cuando este método regresa, contiene el valor doble asociado con el nombre especificado, si se encuentra el nombre; de lo contrario, null. Este parámetro se pasa sin inicializar. |

### ReturnValue

true si el valor se recupera con éxito; de lo contrario, false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
