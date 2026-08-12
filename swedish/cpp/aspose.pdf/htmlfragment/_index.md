---
title: "Aspose::Pdf::HtmlFragment klass"
linktitle: "HtmlFragment"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlFragment klass. Representerar html-fragment i C++."
type: docs
weight: 7100
url: /sv/cpp/aspose.pdf/htmlfragment/
---
## HtmlFragment class


Representerar HTML‑fragment.

```cpp
class HtmlFragment : public Aspose::Pdf::FormattedFragment
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klonar html-fragment. |
| [get_HtmlLoadOptions](./get_htmlloadoptions/)() const | Hämtar [HtmlLoadOptions](../htmlloadoptions/) som kommer att användas för inläsning (och rendering) av HTML i detta klassinstans. Använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den där instansen (t.ex. när denna eller den där instansen ska använda en specifik BasePath för importerad HTML eller en specifik laddare för externa resurser). Om parametern är standard (null) kommer standardalternativen för HTML-inläsning att användas. |
| [get_IsBreakWords](./get_isbreakwords/)() const | Hämtar ordavbrott. |
| [get_IsParagraphHasMargin](./get_isparagraphhasmargin/)() const | Hämtar om stycket har standardmarginal, annars är marginalen 0. |
| [get_Rectangle](./get_rectangle/)() const | Hämtar rektangeln för [HtmlFragment](./). |
| [get_TextState](./get_textstate/)() const | Hämtar teckensnitt. |
| [HtmlFragment](./htmlfragment/)(const System::String\&) | Initierar en ny instans av klassen [HtmlFragment](./). |
| [set_HtmlLoadOptions](./set_htmlloadoptions/)(const System::SharedPtr\<Aspose::Pdf::HtmlLoadOptions\>\&) | Ställer in [HtmlLoadOptions](../htmlloadoptions/) som kommer att användas för inläsning (och rendering) av HTML i detta klassinstans. Använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den där instansen (t.ex. när denna eller den där instansen ska använda en specifik BasePath för importerad HTML eller en specifik laddare för externa resurser). Om parametern är standard (null) kommer standardalternativen för HTML-inläsning att användas. |
| [set_IsBreakWords](./set_isbreakwords/)(bool) | Ställer in ordavbrott. |
| [set_IsParagraphHasMargin](./set_isparagraphhasmargin/)(bool) | Ställer in om stycket har standardmarginal, annars är marginalen 0. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Ställer in teckensnitt. |
## Se även

* Class [FormattedFragment](../formattedfragment/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
