---
title: "Aspose::Pdf::Annotations::ActionCollection clase"
linktitle: "ActionCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::ActionCollection clase. Colección de acciones en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.annotations/actioncollection/
---
## ActionCollection class


[Collection](../../aspose.pdf/collection/) of actions.

```cpp
class ActionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<PdfAction>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<PdfAction\>\&) override | Agrega una nueva acción a la colección. |
| [Clear](./clear/)() override | Borrar colección. |
| [Contains](./contains/)(const System::SharedPtr\<PdfAction\>\&) const override | Devuelve true si el elemento dado está presente en la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<PdfAction\>\>, int32_t) override | Copia la matriz de acciones en la colección. |
| [Delete](./delete/)(int32_t) | Elimina la acción de la colección por índice. |
| [Delete](./delete/)() | Eliminar todas las acciones. |
| [get_Count](./get_count/)() const override | Recuento de acciones en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Devuelve true si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve true si el objeto está sincronizado. |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene el objeto de sincronización. |
| [GetEnumerator](./getenumerator/)() override | Devuelve el enumerador para la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene la acción por su índice. |
| [Remove](./remove/)(const System::SharedPtr\<PdfAction\>\&) override | Elimina el elemento de la colección. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
