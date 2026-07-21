---
title: "Aspose::Pdf::Forms::OptionCollection class"
linktitle: "OptionCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::OptionCollection class. Clase que representa la colección de opciones del campo de elección en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.pdf.forms/optioncollection/
---
## OptionCollection class


Clase que representa la colección de opciones del campo de elección.

```cpp
class OptionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Option>>
```

## Métodos

| Método | Descripción |
| --- | --- |
|  | [Add](./add/)(const System::SharedPtr\<Option\>\&) override | Agrega un elemento a la colección, lanza NotImplementedException. |
. |
| [Clear](./clear/)() override | Elimina todos los elementos de la colección. |
|  | [Contains](./contains/)(const System::SharedPtr\<Option\>\&) const override | Comprueba si el elemento existe en la colección, lanza NotImplementedException |
. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Option\>\>, int32_t) override | Copia las opciones en una matriz. |
| [get](./get/)(int32_t) | Obtiene la opción por índice. |
| [get](./get/)(const System::String\&) | Obtiene la opción de la colección por nombre de opción. |
| [get_Count](./get_count/)() const override | Obtiene el número de opciones. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve true si el objeto está sincronizado. |
| [get_SyncRoot](./get_syncroot/)() const | Objeto de sincronización de la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para las opciones en la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene la opción por índice. |
| [idx_get](./idx_get/)(const System::String\&) | Obtiene la opción por su nombre. |
|  | [Remove](./remove/)(const System::SharedPtr\<Option\>\&) override | Elimina el elemento de la colección, lanza NotImplementedException |
. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
