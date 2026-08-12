---
title: "Метод Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics"
linktitle: "CreateComparisonStatistics"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics. Получает статистику сравнения в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/
---
## TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) method


Получает статистику сравнения.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &diffs)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| различия | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | Список изменений. |

### ReturnValue

Статистика.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) method


Получает статистику сравнения документов.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &diffs)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| различия | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\& | Список изменений. |

### ReturnValue

Статистика.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
