---
title: Aspose::Pdf::Text::SystemFontsSubstitution class
linktitle: SystemFontsSubstitution
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::SystemFontsSubstitution class. Represents a class for font substitution strategy that substitutes fonts with system fonts in C++.'
type: docs
weight: 3200
url: /cpp/aspose.pdf.text/systemfontssubstitution/
---
## SystemFontsSubstitution class


Represents a class for font substitution strategy that substitutes fonts with system fonts.

```cpp
class SystemFontsSubstitution : public Aspose::Pdf::Text::FontSubstitution
```

## Methods

| Method | Description |
| --- | --- |
| [get_DefaultFont](./get_defaultfont/)() | Gets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ([FontCategories](../)). |
| [get_FontCategories](./get_fontcategories/)() const | Gets substitution font categories that should be substituted with system fonts. |
| [set_DefaultFont](./set_defaultfont/)(System::SharedPtr\<Font\>) | Sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ([FontCategories](../)). |
| [set_FontCategories](./set_fontcategories/)(SubstitutionFontCategories) | Sets substitution font categories that should be substituted with system fonts. |
| [SystemFontsSubstitution](./systemfontssubstitution/)(SubstitutionFontCategories) | Initializes a new instance of [SystemFontsSubstitution](./) class. |
## See Also

* Class [FontSubstitution](../fontsubstitution/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
