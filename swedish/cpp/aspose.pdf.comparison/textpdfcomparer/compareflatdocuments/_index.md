---
title: "Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments metod"
linktitle: "CompareFlatDocuments"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments metod. Jämför två dokument sida för sida. Dokumenten jämförs som en helhet. Innan text jämförs, kombineras texterna från dokumentens sidor till en enda text i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## TextPdfComparer::CompareFlatDocuments(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) method


Jämför två dokument sida för sida. Dokumenten jämförs som helhet. Innan text jämförs kombineras texterna på dokumentens sidor till en enda text.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Första dokumentet. |
| document2 | const System::SharedPtr\<Document\>\& | Andra dokumentet. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) alternativ. |

### ReturnValue

Lista över ändringar.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareFlatDocuments(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) method


Jämför två dokument sida för sida. Resultatet sparas i en PDF‑fil. Dokumenten jämförs som helhet. Innan text jämförs kombineras texterna på dokumentens sidor till en enda text.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options, const System::String &resultPdfDocumentPath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Första dokumentet. |
| document2 | const System::SharedPtr\<Document\>\& | Andra dokumentet. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) alternativ. |
| resultPdfDocumentPath | const System::String\& | Sökväg till pdf-filen för att spara jämförelseresultaten. |

### ReturnValue

Lista över ändringar.

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
