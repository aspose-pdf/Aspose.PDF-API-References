---
title: "Aspose::Pdf::Forms::ChoiceField-klass"
linktitle: "ChoiceField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::ChoiceField klass. Representerar basklass för valfält i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.forms/choicefield/
---
## ChoiceField class


Representerar basklass för valfält.

```cpp
class ChoiceField : public Aspose::Pdf::Forms::Field
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AddOption](./addoption/)(System::String) | Lägger till ett nytt alternativ med angivet namn. |
| virtual [AddOption](./addoption/)(System::String, System::String) | Lägger till ett nytt alternativ med angivet exportvärde och namn. |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för [ChoiceField](./). |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Document\>\&) | Skapar valfält (för Generator) |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för [ChoiceField](./). |
| virtual [DeleteOption](./deleteoption/)(System::String) | Tar bort alternativet efter dess namn. |
| [get_CommitImmediately](./get_commitimmediately/)() | Hämtar flaggan för bekräftelse vid urvalsförändring. |
| [get_MultiSelect](./get_multiselect/)() | Hämtar flervalsflagga. |
| virtual [get_Options](./get_options/)() | Hämtar samling av valalternativ. |
| virtual [get_Selected](./get_selected/)() | Hämtar index för valt alternativ. Denna egenskap tillåter att ändra urvalet. |
| virtual [get_SelectedItems](./get_selecteditems/)() | Hämtar array av valda objekt. För flervalslista innehåller arrayen mer än ett objekt. För enkelvallista innehåller den ett enda objekt. |
| [get_Value](./get_value/)() override | Hämtar värdet på fältet. |
| [set_CommitImmediately](./set_commitimmediately/)(bool) | Ställer in flaggan för bekräftelse vid urvalsförändring. |
| [set_MultiSelect](./set_multiselect/)(bool) | Ställer in flervalsflagga. |
| virtual [set_Selected](./set_selected/)(int32_t) | Ställer in index för valt alternativ. Denna egenskap tillåter att ändra urvalet. |
| virtual [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) | Ställer in array av valda objekt. För flervalslista innehåller arrayen mer än ett objekt. För enkelvallista innehåller den ett enda objekt. |
| [set_Value](./set_value/)(System::String) override | Ställer in värdet på fältet. |
## Se även

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
