---
title: "Aspose::Pdf::PageNumberStamp класс"
linktitle: "PageNumberStamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PageNumberStamp класс. Представляет штамп номера страницы и используется для нумерации страниц в C++."
type: docs
weight: 14200
url: /ru/cpp/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class


Представляет штамп номера страницы и используется для нумерации страниц.

```cpp
class PageNumberStamp : public Aspose::Pdf::TextStamp
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Format](./get_format/)() const | Строковое значение для штамповки номеров страниц. Значение должно включать символ '#', который заменяется номером страницы в процессе штамповки. |
| [get_NumberingStyle](./get_numberingstyle/)() const | Стиль нумерации, используемый этим штампом. |
| [get_StartingNumber](./get_startingnumber/)() const | Получает значение номера начальной страницы. Последующие страницы будут нумероваться, начиная с этого значения. |
| [PageNumberStamp](./pagenumberstamp/)(const System::String\&) | Инициализирует новый экземпляр класса [PageNumberStamp](./). |
| [PageNumberStamp](./pagenumberstamp/)() | Инициализирует новый экземпляр класса [PageNumberStamp](./). Формат установлен в "#". |
| [PageNumberStamp](./pagenumberstamp/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Создаёт [PageNumberStamp](./) с помощью отформатированного текста. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Добавляет номер страницы. |
| [set_Format](./set_format/)(const System::String\&) | Строковое значение для штамповки номеров страниц. Значение должно включать символ '#', который заменяется номером страницы в процессе штамповки. |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Стиль нумерации, используемый этим штампом. |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Устанавливает значение номера начальной страницы. Последующие страницы будут нумероваться, начиная с этого значения. |
## См. также

* Class [TextStamp](../textstamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
