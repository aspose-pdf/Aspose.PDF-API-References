---
title: "Метод Aspose::Pdf::Comparison::GraphicalPdfComparer::GetDifference"
linktitle: "GetDifference"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Comparison::GraphicalPdfComparer::GetDifference. Получает различия между изображениями страниц. Результат содержит изображение первой сравниваемой страницы и массив различий в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.comparison/graphicalpdfcomparer/getdifference/
---
## GraphicalPdfComparer::GetDifference method


Получает различия между изображениями страниц. Результат содержит изображение первой сравниваемой страницы и массив различий.

```cpp
System::SharedPtr<ImagesDifference> Aspose::Pdf::Comparison::GraphicalPdfComparer::GetDifference(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | Первая страница. |
| page2 | const System::SharedPtr\<Page\>\& | Вторая страница. |

### ReturnValue

Экземпляр [ImagesDifference](../../imagesdifference/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImagesDifference](../../imagesdifference/)
* Class [Page](../../../aspose.pdf/page/)
* Class [GraphicalPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
