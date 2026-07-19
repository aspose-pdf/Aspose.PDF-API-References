---
title: "Aspose::Pdf::Forms::TextBoxField class"
linktitle: "TextBoxField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::TextBoxField class. Класс, представляющий поле текстового ввода в C++."
type: docs
weight: 2900
url: /ru/cpp/aspose.pdf.forms/textboxfield/
---
## TextBoxField class


Класс, представляющий поле текстового поля.

```cpp
class TextBoxField : public Aspose::Pdf::Forms::Field
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddBarcode](./addbarcode/)(const System::String\&) | Добавляет штрих‑код 128 в поле. Значение [Field](../field/) будет изменено на код, и поле станет только для чтения. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::Drawing::Image\>\&) | Добавляет изображение в ресурсы поля и отрисовывает его. |
| [get_ForceCombs](./get_forcecombs/)() | Получает флаг, указывающий, разделено ли поле на позиционные интервалы. |
| [get_MaxLen](./get_maxlen/)() | Получает максимальную длину текста в поле. |
| [get_Multiline](./get_multiline/)() | Получает флаг многократных строк поля. Если Multiline равно true, поле может содержать несколько строк текста. |
| [get_Scrollable](./get_scrollable/)() | Получает флаг прокручиваемости поля. Если true, поле можно прокручивать. |
| [get_SpellCheck](./get_spellcheck/)() | Получает флаг проверки орфографии для поля. Если true, поле будет проверяться на орфографию. |
| [get_TextVerticalAlignment](./get_textverticalalignment/)() const | Получает вертикальное выравнивание текста для аннотации. |
| [get_Value](./get_value/)() override | Получает значение поля. |
| [set_ForceCombs](./set_forcecombs/)(bool) | Устанавливает флаг, указывающий, разделено ли поле на позиционные ячейки. |
| [set_MaxLen](./set_maxlen/)(int32_t) | Устанавливает максимальную длину текста в поле. |
| [set_Multiline](./set_multiline/)(bool) | Устанавливает флаг многострочности поля. Если Multiline равно true, поле может содержать несколько строк текста. |
| [set_Scrollable](./set_scrollable/)(bool) | Устанавливает флаг прокручиваемости поля. Если true, поле можно прокручивать. |
| [set_SpellCheck](./set_spellcheck/)(bool) | Устанавливает флаг проверки орфографии для поля. Если true, поле будет проверяться на орфографию. |
| [set_TextVerticalAlignment](./set_textverticalalignment/)(Aspose::Pdf::VerticalAlignment) | Устанавливает вертикальное выравнивание текста для аннотации. |
| [set_Value](./set_value/)(System::String) override | Устанавливает значение поля. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Document\>\&) | Конструктор, который следует использовать с Generator. |
| [TextBoxField](./textboxfield/)() | Создать экземпляр [TextBoxField](./). |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор поля TextBox. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Конструктор поля TextBox. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор поля TextBox. |
## См. также

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
