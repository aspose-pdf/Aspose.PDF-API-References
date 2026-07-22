---
title: "Aspose::Pdf::Forms::TextBoxField klass"
linktitle: "TextBoxField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::TextBoxField klass. Klass som representerar ett textboxfält i C++."
type: docs
weight: 2900
url: /sv/cpp/aspose.pdf.forms/textboxfield/
---
## TextBoxField class


Klass som representerar textrutefält.

```cpp
class TextBoxField : public Aspose::Pdf::Forms::Field
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddBarcode](./addbarcode/)(const System::String\&) | Lägger till streckkod 128 i fältet. [Field](../field/) värdet kommer att ändras till koden och fältet blir skrivskyddat. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::Drawing::Image\>\&) | Lägger till en bild i fältets resurser och ritar den. |
| [get_ForceCombs](./get_forcecombs/)() | Hämtar flaggan som indikerar om fältet är indelat i separata positioner. |
| [get_MaxLen](./get_maxlen/)() | Hämtar maximal längd för text i fältet. |
| [get_Multiline](./get_multiline/)() | Hämtar flerradig-flaggan för fältet. Om Multiline är true kan fältet innehålla flera rader text. |
| [get_Scrollable](./get_scrollable/)() | Hämtar rullningsbar-flaggan för fältet. Om true kan fältet rullas. |
| [get_SpellCheck](./get_spellcheck/)() | Hämtar stavningskontroll-flaggan för fältet. Om true ska fältet stavningskontrolleras. |
| [get_TextVerticalAlignment](./get_textverticalalignment/)() const | Hämtar vertikal textjustering för annotation. |
| [get_Value](./get_value/)() override | Hämtar värdet på fältet. |
| [set_ForceCombs](./set_forcecombs/)(bool) | Ställer in flagga som indikerar om fältet är uppdelat i separata positioner. |
| [set_MaxLen](./set_maxlen/)(int32_t) | Ställer in maximal längd för text i fältet. |
| [set_Multiline](./set_multiline/)(bool) | Ställer in flerradig flagga för fältet. Om Multiline är true kan fältet innehålla flera rader text. |
| [set_Scrollable](./set_scrollable/)(bool) | Ställer in rullningsbar flagga för fältet. Om true kan fältet rullas. |
| [set_SpellCheck](./set_spellcheck/)(bool) | Ställer in stavningskontroll-flagga för fältet. Om true ska fältet stavningskontrolleras. |
| [set_TextVerticalAlignment](./set_textverticalalignment/)(Aspose::Pdf::VerticalAlignment) | Ställer in vertikal textjustering för annotationen. |
| [set_Value](./set_value/)(System::String) override | Ställer in värdet på fältet. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Document\>\&) | Konstruktor som bör användas med Generator. |
| [TextBoxField](./textboxfield/)() | Skapa en instans av [TextBoxField](./). |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för TextBox-fältet. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Konstruktor för TextBox-fältet. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för TextBox-fältet. |
## Se även

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
