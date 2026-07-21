---
title: "Clase Aspose::Pdf::OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::OutlineCollection. Representa la jerarquía del esquema del documento en C++."
type: docs
weight: 12500
url: /es/cpp/aspose.pdf/outlinecollection/
---
## OutlineCollection class


Representa la jerarquía del esquema del documento.

```cpp
class OutlineCollection : public Aspose::Pdf::Outlines
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Agrega un elemento de esquema a la colección. |
| [Clear](./clear/)() override | Limpia todos los elementos de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Comprueba si la colección contiene el elemento dado. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Copia los elementos de esquema a un [System.Array](../../system/array/), comenzando en un índice particular de [System.Array](../../system/array/). |
| [Delete](./delete/)() | Elimina todos los elementos de esquema del esquema del documento. |
| [Delete](./delete/)(const System::String\&) | Elimina el elemento de esquema con el título especificado del esquema del documento. |
| [get_Count](./get_count/)() const override | Recuento de elementos de la colección. Por favor, no lo confunda con VisibleCount: VisibleCount obtiene el número de elementos de esquema visibles en todos los niveles. |
| [get_First](./get_first/)() const | Obtiene un elemento de esquema que representa el primer elemento de nivel superior en el esquema. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para subprocesos). |
| [get_Last](./get_last/)() | Obtiene un elemento de esquema que representa el último elemento de nivel superior en el esquema. |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso a esta colección. |
| [get_VisibleCount](./get_visiblecount/)() override | Count es la suma del número de elementos de esquema descendentes visibles en todos los niveles. [Note](../note/): por favor, no lo confunda con Count, que es el número de elementos en la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene un elemento de esquema de la colección por índice. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Siempre lanza NotImplementedException |
| [Remove](./remove/)(int32_t) | Elimina el elemento por índice. |
## Ver también

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
