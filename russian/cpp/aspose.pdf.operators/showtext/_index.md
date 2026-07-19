---
title: "Aspose::Pdf::Operators::ShowText класс"
linktitle: "ShowText"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::ShowText класс. Класс, представляющий оператор Tj (отображает текст) в C++."
type: docs
weight: 7700
url: /ru/cpp/aspose.pdf.operators/showtext/
---
## ShowText class


Класс, представляющий оператор Tj (отображение текста).

```cpp
class ShowText : public Aspose::Pdf::Operators::TextShowOperator
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Принимает объект посетителя для обработки оператора. |
| [get_Text](./get_text/)() override | [Text](../../aspose.pdf.text/) оператора. |
| [set_Text](./set_text/)(System::String) override | [Text](../../aspose.pdf.text/) оператора. |
| [ShowText](./showtext/)(int32_t, const System::String\&) | Инициализирует оператор Tj. |
| [ShowText](./showtext/)(const System::String\&) | Инициализирует оператор Tj. |
| [ShowText](./showtext/)(const System::String\&, const System::SharedPtr\<Text::Font\>\&) | Инициализирует оператор Tj. |
| [ShowText](./showtext/)() | Инициализирует оператор Tj. |
| [ToString](./tostring/)() const override | Создаёт текстовый код оператора. |
## См. также

* Class [TextShowOperator](../textshowoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
