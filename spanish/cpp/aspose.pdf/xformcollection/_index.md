---
title: "Aspose::Pdf::XFormCollection clase"
linktitle: "XFormCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::XFormCollection clase. Clase representa colección de XFormCollection en C++."
type: docs
weight: 19600
url: /es/cpp/aspose.pdf/xformcollection/
---
## XFormCollection class


Clase representa colección de [XFormCollection](./).

```cpp
class XFormCollection : public System::Collections::Generic::ICollection<System::SharedPtr<XForm>>,
                        public Aspose::Pdf::ISupportsMemoryCleanup
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XForm\>\&) override | Agrega nuevo [XForm](../xform/) a la colección. |
| [Clear](./clear/)() override | Limpia todos los elementos de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<XForm\>\&) const override | Determina si la colección contiene un valor específico. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<XForm\>\>, int32_t) override | Copia [XFormCollection](./) a la colección. |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(const System::SharedPtr\<XForm\>\&) |  |
| [Delete](./delete/)(int32_t) | Elimina [XForm](../xform/) de la colección. |
| [Delete](./delete/)() | Elimina todos los XForms de la colección. |
| [Delete](./delete/)(const System::String\&) | Elimina [XForm](../xform/) de la colección por nombre del formulario. |
| [FreeMemory](./freememory/)() override | Borra datos en caché, libera memoria, etc. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de XForms en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve true si el objeto está sincronizado. |
| [get_SyncRoot](./get_syncroot/)() const | Objeto de sincronización. |
| [GetEnumerator](./getenumerator/)() override | Devuelve enumerador de la colección. |
| [GetFormName](./getformname/)(const System::SharedPtr\<XForm\>\&) | Devuelve el nombre del formulario en esta colección de formularios. |
| [idx_get](./idx_get/)(int32_t) | Devuelve [XForm](../xform/) por índice. |
| [idx_get](./idx_get/)(const System::String\&) | Devuelve [XForm](../xform/) por su nombre. Se lanza una excepción si [XForm](../xform/) con el nombre especificado no se encuentra. |
| [Remove](./remove/)(const System::SharedPtr\<XForm\>\&) override | Elimina el elemento especificado de la colección. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
