---
title: "Aspose::Pdf::CollectionItem::TryGetDateTimeValue método"
linktitle: "TryGetDateTimeValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::CollectionItem::TryGetDateTimeValue método. Intenta obtener el valor de tipo DateTime del elemento de colección mediante el nombre especificado en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf/collectionitem/trygetdatetimevalue/
---
## CollectionItem::TryGetDateTimeValue method


Intenta obtener el valor de tipo DateTime del elemento de la colección mediante el nombre especificado.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetDateTimeValue(const System::String &name, System::SharedPtr<CollectionItem::Value<System::DateTime>> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const System::String\& | El nombre del valor a recuperar. |
| valor | System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\& | Cuando este método regresa, contiene el valor asociado con el nombre especificado, si se encuentra el nombre; de lo contrario, null. Este parámetro se pasa sin inicializar. |

### ReturnValue

true si el valor asociado con el nombre especificado se recupera con éxito; de lo contrario, false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [DateTime](../../../system/datetime/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
