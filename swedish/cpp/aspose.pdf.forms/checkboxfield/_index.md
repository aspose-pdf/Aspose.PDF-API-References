---
title: "Aspose::Pdf::Forms::CheckboxField klass"
linktitle: "CheckboxField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::CheckboxField klass. Klass som representerar kryssrutfält i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.forms/checkboxfield/
---
## CheckboxField class


Klassen som representerar kryssrutfält.

```cpp
class CheckboxField : public Aspose::Pdf::Forms::Field
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddOption](./addoption/)(const System::String\&) | Lägger till en ny kryssruta i en kryssrutsgrupp, där högst en av kryssrutorna kan vara markerad åt gången. Den nya kryssrutan läggs till längst ner i gruppen. |
| [AddOption](./addoption/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Lägger till en ny kryssruta i en kryssrutsgrupp, där högst en av kryssrutorna kan vara markerad åt gången. |
| [AddOption](./addoption/)(const System::String\&, int32_t, const System::SharedPtr\<Rectangle\>\&) | Lägger till en ny kryssruta i en kryssrutsgrupp, där högst en av kryssrutorna kan vara markerad åt gången. |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för [CheckboxField](./) klass. |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för [CheckboxField](./) klass. |
| [CheckboxField](./checkboxfield/)() | Skapa en instans av [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Document\>\&) | Konstruktor att använda med Generator. |
| [Clone](./clone/)() override | Klona kryssrutan. |
| [get_ActiveState](./get_activestate/)() override | Hämtar aktuellt annoteringsutseende. |
| [get_AllowedStates](./get_allowedstates/)() | Returnerar lista över tillåtna tillstånd. |
| [get_Checked](./get_checked/)() | Hämtar tillstånd för kryssruta. |
| [get_ExportValue](./get_exportvalue/)() | Hämtar exportvärde för CheckBox-fältet. |
| [get_Style](./get_style/)() | Hämtar stil för kryssruta. |
| [get_Value](./get_value/)() override | Hämtar värde för kryssruta-fältet. |
| [set_ActiveState](./set_activestate/)(System::String) override | Ställer in aktuellt annoteringsutseende. |
| [set_Checked](./set_checked/)(bool) | Ställer in tillstånd för kryssruta. |
| [set_ExportValue](./set_exportvalue/)(const System::String\&) | Ställer in exportvärde för CheckBox-fältet. |
| [set_Style](./set_style/)(BoxStyle) | Ställer in stil för kryssruta. |
| [set_Value](./set_value/)(System::String) override | Ställer in värde för kryssruta-fältet. |
## Se även

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
