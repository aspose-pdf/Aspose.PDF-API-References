---
title: "Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage metod"
linktitle: "CompareDocumentsPageByPage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage metod. Jämför två dokument sida för sida i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) method


Jämför två dokument sida för sida.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Första dokumentet.. |
| document2 | const System::SharedPtr\<Document\>\& | Andra dokumentet. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) alternativ. |

### ReturnValue

Lista över ändringar per sida.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) method


Jämför två dokument sida för sida. Resultatet sparas i en PDF‑fil.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options, const System::String &resultPdfDocumentPath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Första dokumentet.. |
| document2 | const System::SharedPtr\<Document\>\& | Andra dokumentet. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) alternativ. |
| resultPdfDocumentPath | const System::String\& | Sökväg till pdf-filen för att spara jämförelseresultaten. |

### ReturnValue

Lista över ändringar per sida.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [String](../../../system/string/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
