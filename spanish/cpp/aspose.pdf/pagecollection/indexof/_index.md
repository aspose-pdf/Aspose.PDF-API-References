---
title: "Aspose::Pdf::PageCollection::IndexOf método"
linktitle: "IndexOf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageCollection::IndexOf método. Devuelve el índice de la página especificada en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf/pagecollection/indexof/
---
## PageCollection::IndexOf method


Devuelve el índice de la página especificada.

```cpp
int32_t Aspose::Pdf::PageCollection::IndexOf(const System::SharedPtr<Page> &entity) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entity | const System::SharedPtr\<Page\>\& | [Page](../../page/) objeto. Los números de página comienzan en 1. |

### ReturnValue

Índice de la página en la colección.
## Observaciones


Los números de página comienzan en 1. Devuelve 0 en caso de que la colección no contenga la página.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
