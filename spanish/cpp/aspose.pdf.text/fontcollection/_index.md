---
title: "Clase Aspose::Pdf::Text::FontCollection"
linktitle: "FontCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::FontCollection. Representa una colección de fuentes en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.pdf.text/fontcollection/
---
## FontCollection class


Representa una colección de fuentes.

```cpp
class FontCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Font>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Font\>\&, System::String\&) | Agrega una nueva fuente a los recursos de fuentes y devuelve el nombre asignado automáticamente al recurso de fuente. |
| [Contains](./contains/)(const System::String\&) const | Comprueba si la fuente existe en la colección de fuentes. |
| [Contains](./contains/)(const System::SharedPtr\<Font\>\&) const override | Determina si la colección contiene un valor específico. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Font\>\>, int32_t) override | Copia toda la colección a una Matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos de objeto [Font](../font/) realmente contenidos en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para toda la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el elemento de fuente en el índice especificado. |
| [idx_get](./idx_get/)(const System::String\&) | Obtiene la fuente de la colección por nombre de fuente. Se lanza una excepción si no se encuentra la fuente. |
| [Remove](./remove/)(const System::SharedPtr\<Font\>\&) override | Elimina el elemento especificado de la colección. |
## Observaciones


[Font](../font/) collections represented by [FontCollection](./) class are used in several scenarios. For example, in resources with [Resources::Fonts](../) property. 
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
