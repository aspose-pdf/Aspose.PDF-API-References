---
title: "Aspose::Pdf::Outlines class"
linktitle: "Outlines"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Outlines class. La clase describe una colección de contornos en C++."
type: docs
weight: 12700
url: /es/cpp/aspose.pdf/outlines/
---
## Outlines class


Clase que describe una colección de esquemas.

```cpp
class Outlines : public System::Collections::Generic::ICollection<System::SharedPtr<OutlineItemCollection>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Agrega un elemento de esquema a la colección. |
| virtual [Clear](./clear/)() | Limpia todos los elementos de la colección. |
| virtual [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const | Siempre lanza NotImplementedException. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) | Copia las entradas del esquema a un [System.Array](../../system/array/), comenzando en un índice particular del [System.Array](../../system/array/). |
| virtual [get_Count](./get_count/)() const | Obtiene el recuento. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Obtiene un valor que indica si la colección es de solo lectura. |
| virtual [get_VisibleCount](./get_visiblecount/)() | Obtiene el número total de elementos de esquema en todos los niveles de la jerarquía del esquema del documento. |
| virtual [GetEnumerator](./getenumerator/)() | Devuelve un enumerador que recorre la colección. |
| virtual [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Elimina el elemento de la colección de esquema. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
