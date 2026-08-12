---
title: "Clase Aspose::Pdf::Text::FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::FontSourceCollection. Representa una colección de fuentes en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.text/fontsourcecollection/
---
## FontSourceCollection class


Representa la colección de fuentes.

```cpp
class FontSourceCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FontSource>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FontSource\>\&) override | Agrega un nuevo objeto de origen de fuente a la colección. |
| [Clear](./clear/)() override | Limpia la colección de orígenes de fuentes. |
| [Contains](./contains/)(const System::SharedPtr\<FontSource\>\&) const override | Determina si un elemento está en la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FontSource\>\>, int32_t) override | Copia toda la colección a una Matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [Delete](./delete/)(const System::SharedPtr\<FontSource\>\&) | Elimina el elemento de origen de fuente. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos de objeto [Font](../font/) realmente contenidos en la colección. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para toda la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el elemento de fuente en el índice especificado. |
| [Remove](./remove/)(const System::SharedPtr\<FontSource\>\&) override | Elimina el elemento de origen de fuente. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
