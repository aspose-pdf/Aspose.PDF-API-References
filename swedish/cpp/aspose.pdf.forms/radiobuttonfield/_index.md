---
title: "Aspose::Pdf::Forms::RadioButtonField-klass"
linktitle: "RadioButtonField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::RadioButtonField-klass. Klassen representerar ett radioknappsfält i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class


Klass som representerar radioknappsfält.

```cpp
class RadioButtonField : public Aspose::Pdf::Forms::ChoiceField
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<RadioButtonOptionField\>\&) | Lägger till ett nytt alternativfält till RadioButton-fältet. |
| [AddOption](./addoption/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Lägg till alternativ för radioknapp med specificerad rektangel. |
| [AddOption](./addoption/)(System::String) override | Lägg till alternativ till radioknappen. |
|  | [get_NoToggleToOff](./get_notoggletooff/)() | Hämtar eller anger flaggan som tillåter radiobuttonen att ha inget valt värde. Om **true** |

, exakt en radioknapp ska vara vald hela tiden; att välja den redan valda knappen har ingen effekt. Om **false**

, att klicka på den valda knappen avmarkerar den, så att ingen knapp är vald. |
| [get_Options](./get_options/)() override | Hämtar samling av alternativ för radioknappen. |
| [get_PageIndex](./get_pageindex/)() override | Hämtar sidans index som innehåller detta RadioButton-fält. |
| [get_Selected](./get_selected/)() override | Hämtar index för valt objekt. Numrering av objekt startar från 1. |
| [get_Style](./get_style/)() | Stil för fältbox. |
| [get_Value](./get_value/)() override | Hämtar fältets värde. |
| [RadioButtonField](./radiobuttonfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Konstruktor för RadiouttonField. |
| [RadioButtonField](./radiobuttonfield/)(const System::SharedPtr\<Document\>\&) | Konstruktor för [RadioButtonField](./). |
|  | [set_NoToggleToOff](./set_notoggletooff/)(bool) | Hämtar eller anger flaggan som tillåter radiobuttonen att ha inget valt värde. Om **true** |

, exakt en radioknapp ska vara vald hela tiden; att välja den redan valda knappen har ingen effekt. Om **false**

, att klicka på den valda knappen avmarkerar den, så att ingen knapp är vald. |
| [set_Selected](./set_selected/)(int32_t) override | Anger index för valt objekt. Numrering av objekt startar från 1. |
| [set_Style](./set_style/)(BoxStyle) | Stil för fältbox. |
| [set_Value](./set_value/)(System::String) override | Anger fältets värde. |
| [SetPosition](./setposition/)(System::SharedPtr\<Point\>) override | Flytta alla underobjekt för radioknappen till angivna positioner på sidan. |
## Se även

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
