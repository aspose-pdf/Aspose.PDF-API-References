---
title: "Clase Aspose::Pdf::ArtifactCollection"
linktitle: "ArtifactCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::ArtifactCollection class. La clase representa una colección de artefactos en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf/artifactcollection/
---
## ArtifactCollection class


Clase que representa una colección de artefactos.

```cpp
class ArtifactCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Artifact>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Artifact\>\&) override | Agrega artefactos a la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Artifact\>\>, int32_t) override | Copia la colección en una matriz. |
| [Delete](./delete/)(const System::SharedPtr\<Artifact\>\&) | Elimina el artefacto especificado. |
| [Delete](./delete/)(int32_t) | Elimina el artefacto por su índice. |
| [FindByValue](./findbyvalue/)(const System::String\&, const System::String\&) | Encuentra artefactos por valor personalizado. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de artefactos en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene si la colección es de solo lectura. Siempre devuelve false. |
| [get_IsSynchronized](./get_issynchronized/)() | ¿Está este objeto sincronizado? |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene el objeto de sincronización de la colección. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador de la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el artefacto por índice. El índice comienza en 1. |
| [Update](./update/)(const System::SharedPtr\<Artifact\>\&) | Actualiza el artefacto dentro de la colección. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
