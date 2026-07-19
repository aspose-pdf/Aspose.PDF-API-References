---
title: "Aspose::Pdf::PageNumber класс"
linktitle: "PageNumber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PageNumber класс. Представляет формат номера страницы, который включает индекс, общее количество страниц и разделитель в C++."
type: docs
weight: 14100
url: /ru/cpp/aspose.pdf/pagenumber/
---
## PageNumber class


Представляет формат номера страницы, включающий индекс, общее количество страниц и разделитель.

```cpp
class PageNumber : public System::Object
```

## Nested classes

* Class [PageIndex](./pageindex/)
* Class [PageTotalNum](./pagetotalnum/)
## Методы

| Метод | Описание |
| --- | --- |
| [get_Delimiter](./get_delimiter/)() const | Получает разделитель, используемый в формате номера страницы. Форматированная строка будет обновлена в соответствии с указанным разделителем. |
| [get_Index](./get_index/)() const | Получает компонент индекса страницы в формате номера страницы. Форматированная строка будет содержать заполнитель для индекса страницы. |
| [get_Offset](./get_offset/)() const | Получает смещение, которое будет добавлено к индексу страницы. |
| [get_TotalNum](./get_totalnum/)() const | Получает компонент общего количества страниц в формате номера страницы. Форматированная строка будет содержать заполнитель для общего количества страниц. |
| [GetPageNumberString](./getpagenumberstring/)(int32_t, int32_t) | Возвращает форматированную строку, представляющую номер страницы на основе текущих настроек. |
| [PageNumber](./pagenumber/)() |  |
| [set_Delimiter](./set_delimiter/)(const System::String\&) | Устанавливает разделитель, используемый в формате номера страницы. Форматированная строка будет обновлена в соответствии с указанным разделителем. |
| [set_Index](./set_index/)(const System::SharedPtr\<PageNumber::PageIndex\>\&) | Устанавливает компонент индекса страницы в формате номера страницы. Форматированная строка будет содержать заполнитель для индекса страницы. |
| [set_Offset](./set_offset/)(int32_t) | Устанавливает смещение, которое будет добавлено к индексу страницы. |
| [set_TotalNum](./set_totalnum/)(const System::SharedPtr\<PageNumber::PageTotalNum\>\&) | Устанавливает компонент общего количества страниц в формате номера страницы. Форматированная строка будет содержать заполнитель для общего количества страниц. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
