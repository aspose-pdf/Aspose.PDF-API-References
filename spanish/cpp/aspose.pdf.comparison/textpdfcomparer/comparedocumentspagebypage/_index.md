---
title: "Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage método"
linktitle: "CompareDocumentsPageByPage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage método. Compara dos documentos página por página en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) method


Compara dos documentos página por página.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Primer documento.. |
| document2 | const System::SharedPtr\<Document\>\& | Segundo documento. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) opciones. |

### ReturnValue

Lista de cambios por página.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) method


Compara dos documentos página por página. El resultado se guarda en un archivo PDF.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options, const System::String &resultPdfDocumentPath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Primer documento.. |
| document2 | const System::SharedPtr\<Document\>\& | Segundo documento. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) opciones. |
| resultPdfDocumentPath | const System::String\& | Ruta al archivo pdf para guardar los resultados de la comparación. |

### ReturnValue

Lista de cambios por página.

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
