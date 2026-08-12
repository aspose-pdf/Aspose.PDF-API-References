---
title: "Clase Aspose::Pdf::EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::EmbeddedFileCollection. Clase que representa la colección de archivos incrustados en C++."
type: docs
weight: 4300
url: /es/cpp/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection class


Clase que representa la colección de archivos incrustados.

```cpp
class EmbeddedFileCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FileSpecification>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FileSpecification\>\&) override | Agrega la especificación de archivo incrustado a la colección. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<FileSpecification\>\&) | Agrega un archivo a los archivos incrustados con la clave especificada. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FileSpecification\>\>, int32_t) override | Copia una matriz de objeto [FileSpecification](../filespecification/) en la colección. |
| [Delete](./delete/)(const System::String\&) | Elimina el archivo incrustado por nombre. |
| [Delete](./delete/)() | Elimina todos los archivos incrustados del documento. |
| [DeleteByKey](./deletebykey/)(const System::String\&) | Elimina el archivo de la colección por su clave en la colección. |
| [FindByName](./findbyname/)(const System::String\&) | Devuelve el archivo incrustado por su nombre. |
| [get_Count](./get_count/)() const override | Obtiene el número de archivos incrustados en la colección. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para subprocesos). |
| [get_Keys](./get_keys/)() | Devuelve la lista de claves de archivos adjuntos. |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso a esta colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve el enumerador de la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el archivo incrustado por su índice. |
| [idx_get](./idx_get/)(const System::String\&) | Obtiene el archivo incrustado por su nombre. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
