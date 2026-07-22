---
title: "Aspose::Pdf::Text::SystemFontsSubstitution klass"
linktitle: "SystemFontsSubstitution"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::SystemFontsSubstitution klass. Representerar en klass för teckensnittsbytesstrategi som ersätter teckensnitt med systemteckensnitt i C++."
type: docs
weight: 3200
url: /sv/cpp/aspose.pdf.text/systemfontssubstitution/
---
## SystemFontsSubstitution class


Representerar en klass för teckensnittssubstitutionsstrategi som ersätter teckensnitt med systemteckensnitt.

```cpp
class SystemFontsSubstitution : public Aspose::Pdf::Text::FontSubstitution
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_DefaultFont](./get_defaultfont/)() | Hämtar standardteckensnitt för ersättning. Teckensnittet används när ingen annan giltig ersättning hittades men det ursprungliga teckensnittet tillhör mål‑ersättningskategorin ([FontCategories](../)). |
| [get_FontCategories](./get_fontcategories/)() const | Hämtar teckensnittskategorier för ersättning som bör ersättas med systemteckensnitt. |
| [set_DefaultFont](./set_defaultfont/)(const System::SharedPtr\<Font\>\&) | Ställer in standardteckensnitt för ersättning. Teckensnittet används när ingen annan giltig ersättning hittades men det ursprungliga teckensnittet tillhör mål‑ersättningskategorin ([FontCategories](../)). |
| [set_FontCategories](./set_fontcategories/)(SubstitutionFontCategories) | Ställer in teckensnittskategorier för ersättning som bör ersättas med systemteckensnitt. |
| [SystemFontsSubstitution](./systemfontssubstitution/)(SubstitutionFontCategories) | Initierar en ny instans av [SystemFontsSubstitution](./) klass. |
## Se även

* Class [FontSubstitution](../fontsubstitution/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
