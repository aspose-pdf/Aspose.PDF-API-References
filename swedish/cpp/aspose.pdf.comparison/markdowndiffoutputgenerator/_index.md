---
title: "Aspose::Pdf::Comparison::MarkdownDiffOutputGenerator klass"
linktitle: "MarkdownDiffOutputGenerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::MarkdownDiffOutputGenerator klass. Representerar en klass för att generera markdown‑representation av textskillnader. På grund av markdown‑syntaxen är det inte möjligt att visa ändringar av blankstegstecken. Urval av ändringar gör att blankstegstecken läggs till runt formatering, annars kommer en markdown‑visare inte att visa texten korrekt. Borttagna radbrytningar indikeras med - paragraftecken i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class


Representerar en klass för att generera Markdown‑representation av textskillnader. På grund av Markdown‑syntaxen är det inte möjligt att visa förändringar av blankstegstecken. Val av förändringar innebär att lägga till blankstegstecken runt formatering, annars kommer en Markdown‑visare inte att visa texten korrekt. Borttagna radbrytningar indikeras med - styckemärke.

```cpp
class MarkdownDiffOutputGenerator : public Aspose::Pdf::Comparison::IStringOutputGenerator,
                                    public Aspose::Pdf::Comparison::IFileOutputGenerator
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [MarkdownDiffOutputGenerator](./markdowndiffoutputgenerator/)() | Skapar en instans av klassen [MarkdownDiffOutputGenerator](./). |
## Se även

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
