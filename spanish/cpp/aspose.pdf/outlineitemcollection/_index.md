---
title: "Clase Aspose::Pdf::OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::OutlineItemCollection. Representa una entrada de esquema en la jerarquía de esquema de un documento PDF en C++."
type: docs
weight: 12600
url: /es/cpp/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class


Representa una entrada del esquema en la jerarquía del esquema del documento PDF.

```cpp
class OutlineItemCollection : public Aspose::Pdf::Outlines
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Agrega un elemento de esquema a la colección. |
| [Clear](./clear/)() override | Limpia todos los elementos de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Comprueba si la colección contiene el elemento dado. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Copia las entradas del esquema a un [System.Array](../../system/array/), comenzando en un índice particular del [System.Array](../../system/array/). |
| [Delete](./delete/)() | Elimina este elemento de esquema de la jerarquía de esquema del documento. |
| [Delete](./delete/)(const System::String\&) | Elimina la entrada de esquema con el nombre especificado de la jerarquía de esquema del documento. |
| [get_Action](./get_action/)() | Obtiene la acción para este elemento de esquema. |
| [get_Bold](./get_bold/)() | Obtiene la bandera de negrita para el texto del título de este elemento de esquema. |
| [get_Color](./get_color/)() | Obtiene el color del texto del título de este elemento de esquema. |
| [get_Count](./get_count/)() const override | Recuento de elementos de la colección. Por favor, no lo confunda con VisibleCount: VisibleCount obtiene el número de elementos de esquema visibles en todos los niveles. |
| [get_Destination](./get_destination/)() | Obtiene el destino de este elemento de esquema. |
| [get_First](./get_first/)() const | Obtiene el elemento de esquema que representa el primer elemento de nivel superior en la jerarquía de esquema. |
| [get_HasNext](./get_hasnext/)() | Comprueba si el elemento de esquema que representa el siguiente elemento relativo a este elemento en la jerarquía de esquema. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene el valor que indica si el acceso a esta colección está sincronizado (seguro para subprocesos). |
| [get_Italic](./get_italic/)() | Obtiene la bandera de cursiva para el texto del título de este elemento de esquema. |
| [get_Last](./get_last/)() | Obtiene el elemento de esquema que representa el último elemento de nivel superior en la jerarquía de esquema. |
| [get_Level](./get_level/)() | Obtiene el nivel de jerarquía del elemento de esquema. |
| [get_Next](./get_next/)() | Obtiene el elemento de esquema que representa el siguiente elemento relativo a este elemento en la jerarquía de esquema. |
| [get_Open](./get_open/)() | Obtiene o establece el estado abierto (true/false) para el elemento de esquema. |
| [get_Parent](./get_parent/)() | Obtiene el objeto padre de este elemento de esquema en la jerarquía de esquema. |
| [get_Prev](./get_prev/)() | Obtiene el elemento de esquema que representa el elemento anterior relativo a este elemento en la jerarquía del esquema. |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene el objeto que puede usarse para sincronizar el acceso a esta colección. |
| [get_Title](./get_title/)() | Obtiene el título de este elemento de esquema. |
| [get_VisibleCount](./get_visiblecount/)() override | Obtiene el número total de elementos de esquema en todos los niveles de la jerarquía del esquema del documento. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el elemento de esquema de la colección usando el índice. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<OutlineItemCollection\>\&) | Inserta el elemento de esquema en la colección en el lugar especificado. |
| [OutlineItemCollection](./outlineitemcollection/)(const System::SharedPtr\<OutlineCollection\>\&) | Inicializa la instancia del elemento de esquema usando el objeto de jerarquía raíz. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Elimina el elemento de la colección de esquema. |
| [Remove](./remove/)(int32_t) | Elimina el elemento por índice. |
| [set_Action](./set_action/)(const System::SharedPtr\<Annotations::PdfAction\>\&) | Establece la acción para este elemento de esquema. |
| [set_Bold](./set_bold/)(bool) | Establece la marca de negrita para el texto del título de este elemento de esquema. |
| [set_Color](./set_color/)(System::Drawing::Color) | Establece el color del texto del título de este elemento de esquema. |
| [set_Destination](./set_destination/)(const System::SharedPtr\<Annotations::IAppointment\>\&) | Establece el destino para este elemento de esquema. |
| [set_Italic](./set_italic/)(bool) | Establece la marca de cursiva para el texto del título de este elemento de esquema. |
| [set_Open](./set_open/)(bool) | Obtiene o establece el estado abierto (true/false) para el elemento de esquema. |
| [set_Title](./set_title/)(const System::String\&) | Establece el título para este elemento de esquema. |
## Ver también

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
