---
title: "Aspose::Pdf::Comparison::HtmlDiffOutputGenerator klass"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::HtmlDiffOutputGenerator klass. Representerar en klass för att generera HTML-representation av textskillnader. Borttagna radbrytningar indikeras av stycketecken i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class


Representerar en klass för att generera HTML‑representation av textskillnader. Borttagna radbrytningar indikeras med ett styckemärke.

```cpp
class HtmlDiffOutputGenerator : public Aspose::Pdf::Comparison::IStringOutputGenerator,
                                public Aspose::Pdf::Comparison::IFileOutputGenerator
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [get_DeleteStyle](./get_deletestyle/)() const | Hämtar och anger CSS‑stilssträngen för Delete‑operationen. Exempel: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_EqualStyle](./get_equalstyle/)() const | Hämtar och anger CSS‑stilssträngen för Equal‑operationen. Exempel: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_InsertStyle](./get_insertstyle/)() const | Hämtar och anger CSS‑stilssträngen för Insert‑operationen. Exempel: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_StrikethroughDeleted](./get_strikethroughdeleted/)() const | Hämta eller ange text-decoration: line-through‑stil för delete‑operationen. Standardvärdet är **False**. |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)() | Skapar en instans av klassen [HtmlDiffOutputGenerator](./). |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&) | Skapar en instans av klassen [HtmlDiffOutputGenerator](./). |
| [set_DeleteStyle](./set_deletestyle/)(const System::String\&) | Hämtar och anger CSS‑stilssträngen för Delete‑operationen. Exempel: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_EqualStyle](./set_equalstyle/)(const System::String\&) | Hämtar och anger CSS‑stilssträngen för Equal‑operationen. Exempel: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_InsertStyle](./set_insertstyle/)(const System::String\&) | Hämtar och anger CSS‑stilssträngen för Insert‑operationen. Exempel: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_StrikethroughDeleted](./set_strikethroughdeleted/)(bool) | Hämta eller ange text-decoration: line-through‑stil för delete‑operationen. Standardvärdet är **False**. |
## Se även

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
