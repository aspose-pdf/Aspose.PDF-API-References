---
title: "Aspose::Pdf::Forms::ListBoxField klass"
linktitle: "ListBoxField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::ListBoxField klass. Klassen representerar ListBox-fält i C++."
type: docs
weight: 1300
url: /sv/cpp/aspose.pdf.forms/listboxfield/
---
## ListBoxField class


Klass representerar ListBox-fält.

```cpp
class ListBoxField : public Aspose::Pdf::Forms::ChoiceField
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_TopIndex](./get_topindex/)() | Hämtar index för det översta synliga elementet i listan. |
| [ListBoxField](./listboxfield/)() | Konstruktor för [ListBoxField](./) att användas i Generatorn. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Skapar ett nytt ListBox-fält. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för ListBox-fält. |
| [set_Selected](./set_selected/)(int32_t) override | Ställer in index för det valda objektet. Objekt numreras från 1. |
| [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) override | Ställer in en array med de valda objekten i flervalslistan. För enkelvalslista returneras en array med ett enda objekt. |
| [set_TopIndex](./set_topindex/)(int32_t) | Ställer in index för det översta synliga elementet i listan. |
## Se även

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
