---
title: "Aspose::Pdf::Operators::TextShowOperator class"
linktitle: "TextShowOperator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::TextShowOperator класс. Абстрактный базовый класс для всех операторов, которые используются для вывода текста (Tj, TJ и т.д.) в C++."
type: docs
weight: 8100
url: /ru/cpp/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class


Абстрактный базовый класс для всех операторов, используемых для вывода текста (Tj, TJ и др.).

```cpp
class TextShowOperator : public Aspose::Pdf::Operators::TextOperator
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_Text](./get_text/)() | Получает текст, который оператор выводит на страницу. |
| virtual [set_Text](./set_text/)(System::String) | Получает текст, который оператор выводит на страницу. |
| [TextShowOperator](./textshowoperator/)() | Инициализирует [TextShowOperator](./). |
| [TextShowOperator](./textshowoperator/)(const System::SharedPtr\<Facades::TextProperties\>\&) | Инициализирует [TextShowOperator](./), который позволяет передать TextProperties. |
## См. также

* Class [TextOperator](../textoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
