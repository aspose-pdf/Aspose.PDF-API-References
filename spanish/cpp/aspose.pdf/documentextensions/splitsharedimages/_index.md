---
title: "Método Aspose::Pdf::DocumentExtensions::SplitSharedImages"
linktitle: "SplitSharedImages"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::DocumentExtensions::SplitSharedImages. Para imágenes en Resources, si dos páginas comparten XImages comunes y en casos similares los divide, creando XImages duplicados en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf/documentextensions/splitsharedimages/
---
## DocumentExtensions::SplitSharedImages method


Para imágenes en [Resources](../../resources/) si dos páginas verifican XImages comunes y en casos similares los divide, creando XImages duplicados.

```cpp
static void Aspose::Pdf::DocumentExtensions::SplitSharedImages(const System::SharedPtr<Document> &doc, const System::SharedPtr<Page> &page_1, const System::SharedPtr<Page> &page_2)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| doc | const System::SharedPtr\<Document\>\& | El documento que contiene ambas colecciones. |
| page_1 | const System::SharedPtr\<Page\>\& | Primera página para comparar. |
| page_2 | const System::SharedPtr\<Page\>\& | Segunda página para comparar/ |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Page](../../page/)
* Class [DocumentExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
