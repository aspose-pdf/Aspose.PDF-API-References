---
title: "Clase Aspose::Pdf::Text::TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextSegmentCollection. Representa una colección de segmentos de texto en C++."
type: docs
weight: 5200
url: /es/cpp/aspose.pdf.text/textsegmentcollection/
---
## TextSegmentCollection class


Representa una colección de segmentos de texto.

```cpp
class TextSegmentCollection : public System::Collections::Generic::ICollection<System::SharedPtr<TextSegment>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<TextSegment\>\&) override | Agrega el elemento de segmento de texto en el índice especificado. |
| [Clear](./clear/)() override | Limpia todos los elementos de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<TextSegment\>\&) const override | Determina si la colección contiene un valor específico. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<TextSegment\>\>, int32_t) override | Copia toda la colección a una Matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos de objeto [TextSegment](../textsegment/) realmente contenidos en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para toda la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el elemento de segmento de texto en el índice especificado. |
| [Remove](./remove/)(const System::SharedPtr\<TextSegment\>\&) override | Elimina el elemento especificado de la colección. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
