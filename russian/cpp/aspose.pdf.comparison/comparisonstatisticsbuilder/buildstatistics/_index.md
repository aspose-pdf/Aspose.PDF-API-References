---
title: "Метод Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics"
linktitle: "BuildStatistics"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics. Создаёт объект статистики для результата сравнения страниц PDF или сравнения плоских документов, при котором сравниваются целые документы, в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.comparison/comparisonstatisticsbuilder/buildstatistics/
---
## ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) method


Создаёт объект статистики для результата сравнения страниц PDF или плоского сравнения документов, при котором сравниваются целые документы.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &diffs)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| различия | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | Список различий. |

### ReturnValue

Экземпляр статистики.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) method


Создаёт объект статистики для результата сравнения страниц PDF‑документа.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &diffs)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| различия | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\& | Список различий. |

### ReturnValue

Экземпляр статистики.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
