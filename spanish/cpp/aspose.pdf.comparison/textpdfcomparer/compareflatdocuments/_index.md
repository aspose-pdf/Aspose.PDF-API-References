---
title: "Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments método"
linktitle: "CompareFlatDocuments"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments método. Compara dos documentos página por página. Los documentos se comparan como un todo. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## TextPdfComparer::CompareFlatDocuments(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) method


Compara dos documentos página por página. Los documentos se comparan como un todo. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Primer documento. |
| document2 | const System::SharedPtr\<Document\>\& | Segundo documento. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) opciones. |

### ReturnValue

Lista de cambios.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareFlatDocuments(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) method


Compara dos documentos página por página. El resultado se guarda en un archivo PDF. Los documentos se comparan como un todo. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options, const System::String &resultPdfDocumentPath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Primer documento. |
| document2 | const System::SharedPtr\<Document\>\& | Segundo documento. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) opciones. |
| resultPdfDocumentPath | const System::String\& | Ruta al archivo pdf para guardar los resultados de la comparación. |

### ReturnValue

Lista de cambios.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [String](../../../system/string/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
