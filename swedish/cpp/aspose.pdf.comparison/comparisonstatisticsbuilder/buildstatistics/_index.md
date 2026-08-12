---
title: "Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics metod"
linktitle: "BuildStatistics"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics metod. Skapar ett statistikobjekt för resultatet av att jämföra PDF‑sidor eller platt dokumentjämförelse där hela dokument jämförs i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.comparison/comparisonstatisticsbuilder/buildstatistics/
---
## ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) method


Skapar ett statistikobjekt för resultatet av att jämföra PDF-sidor eller platt dokumentjämförelse där hela dokument jämförs.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &diffs)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| diffar | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | Listan över skillnader. |

### ReturnValue

En statistikinstans.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) method


Skapar ett statistikobjekt för resultatet av en sidjämförelse av ett PDF-dokument.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &diffs)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| diffar | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\& | Listan över skillnader. |

### ReturnValue

En statistikinstans.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
