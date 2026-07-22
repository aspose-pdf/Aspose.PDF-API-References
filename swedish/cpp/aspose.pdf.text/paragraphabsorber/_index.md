---
title: "Aspose::Pdf::Text::ParagraphAbsorber klass"
linktitle: "ParagraphAbsorber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::ParagraphAbsorber-klass. Representerar ett absorberingsobjekt för sidstrukturobjekt såsom sektioner och stycken. Utför sökning efter sektioner och stycken i text och ger åtkomst till rektanglar och polygoner som beskriver det i textkoordinatrymden. Utför också sökning av textsegment och ger åtkomst till sökresultat via TextFragments-samlingar grupperade efter strukturelement i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class


Representerar ett absorberingsobjekt för sidstrukturobjekt såsom avsnitt och stycken. Utför sökning efter avsnitt och stycken i text och ger åtkomst till rektanglar och polygoner som beskriver dem i textkoordinatrymden. Utför också sökning efter textsegment och ger åtkomst till sökresultaten via samlingarna [TextFragments](../) grupperade efter strukturelement.

```cpp
class ParagraphAbsorber : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsMulticolumnParagraphsAllowed](./get_ismulticolumnparagraphsallowed/)() const | Hämtar värdet som indikerar om startlinjerna i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt. |
| [get_PageMarkups](./get_pagemarkups/)() const | Hämtar samling av [PageMarkup](../pagemarkup/) som absorberades. |
| [get_ParagraphAbsorberOptions](./get_paragraphabsorberoptions/)() const | Hämtar [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [get_SectionsSearchDepth](./get_sectionssearchdepth/)() const | Hämtar värdet som anger hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken osv) och tre sökningar för vertikalt delade (kolumner). |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Hämtar [TextReplaceOptions](../textreplaceoptions/). |
| [ParagraphAbsorber](./paragraphabsorber/)() | Initierar en ny instans av [ParagraphAbsorber](./) som utför sökning efter sektioner/stycken i dokumentet eller sidan. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t) | Initierar en ny instans av [ParagraphAbsorber](./) som utför sökning efter sektioner/stycken i dokumentet eller sidan. |
| [ParagraphAbsorber](./paragraphabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Initierar en ny instans av [ParagraphAbsorber](./) som utför sökning efter sektioner/stycken i dokumentet eller sidan med de angivna parametrarna. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t, const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Initierar en ny instans av [ParagraphAbsorber](./) som utför sökning efter sektioner/stycken i dokumentet eller sidan med de angivna parametrarna. |
| [set_IsMulticolumnParagraphsAllowed](./set_ismulticolumnparagraphsallowed/)(bool) | Ställer in värdet som indikerar om startlinjerna i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt. |
| [set_ParagraphAbsorberOptions](./set_paragraphabsorberoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Ställer in [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [set_SectionsSearchDepth](./set_sectionssearchdepth/)(int32_t) | Ställer in värdet som anger hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken osv) och tre sökningar för vertikalt delade (kolumner). |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Ställer in [TextReplaceOptions](../textreplaceoptions/). |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Utför sökning efter sektioner och stycken i det angivna [Document](../../aspose.pdf/document/). |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Utför sökning på den angivna [Page](../../aspose.pdf/page/). |
## Anmärkningar


När sökningen är klar kommer samlingen [ParagraphAbsorber::PageMarkups](../) att innehålla [PageMarkup](../pagemarkup/)-objekt som representerar sidstrukturen genom samlingar av [MarkupSection](../markupsection/) och [MarkupParagraph](../markupparagraph/). [TextFragment](../textfragment/)-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv).
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
