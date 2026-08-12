---
title: "Clase Aspose::Pdf::CollectionItem"
linktitle: "CollectionItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::CollectionItem. Representa una clase de elemento de colección. El elemento de colección contiene los datos descritos por el esquema de colección en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.pdf/collectionitem/
---
## CollectionItem class


Representa una clase de elemento de colección. El elemento de colección contiene los datos descritos por el esquema de la colección.

```cpp
class CollectionItem : public System::Object
```

## Nested classes

* Class [Value](./value/)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AllNames](./get_allnames/)() | Obtiene una colección de todos los nombres de los valores del elemento de colección. |
| [get_IsEmpty](./get_isempty/)() | Obtiene un valor que indica si el elemento de la colección está vacío. |
| [HasName](./hasname/)(const System::String\&) | Comprueba si el nombre dado existe en el elemento de la colección. |
| [TryGetDateTimeValue](./trygetdatetimevalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\&) | Intenta obtener el valor de tipo DateTime del elemento de la colección mediante el nombre especificado. |
| [TryGetDoubleValue](./trygetdoublevalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<double\>\>\&) | Intenta obtener el valor double para el nombre especificado del elemento de la colección. |
| [TryGetIntValue](./trygetintvalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\&) | Intenta obtener el valor entero para un nombre especificado del elemento de la colección. |
| [TryGetTextValue](./trygettextvalue/)(const System::String\&, System::SharedPtr\<CollectionItem::Value\<System::String\>\>\&) | Intenta obtener el valor de texto con el nombre especificado del elemento de la colección. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
