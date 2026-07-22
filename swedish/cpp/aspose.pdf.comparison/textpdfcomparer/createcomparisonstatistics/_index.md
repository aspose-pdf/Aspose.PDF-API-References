---
title: "Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics metod"
linktitle: "CreateComparisonStatistics"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics metod. Hämtar jämförelsestatistik i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/
---
## TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) method


Hämtar jämförelsestatistik.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &diffs)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| diffar | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | Listan över ändringar. |

### ReturnValue

Statistiken.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) method


Hämtar statistik för dokumentjämförelse.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &diffs)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| diffar | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\& | Listan över ändringar. |

### ReturnValue

Statistiken.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
