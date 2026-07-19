---
title: "Метод Aspose::Pdf::Comparison::TextPdfComparer::ComparePages"
linktitle: "ComparePages"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Comparison::TextPdfComparer::ComparePages. Сравнивает страницы документа в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.comparison/textpdfcomparer/comparepages/
---
## TextPdfComparer::ComparePages method


Сравнивает страницы документов.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::ComparePages(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::SharedPtr<ComparisonOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | Первая страница. |
| page2 | const System::SharedPtr\<Page\>\& | Вторая страница. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Сравнение](../../) параметры. |

### ReturnValue

Список изменений.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Page](../../../aspose.pdf/page/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
