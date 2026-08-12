---
title: "Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute method"
linktitle: "TrySubstitute"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute method. Substituerar originalteckensnitt med ett annat teckensnitt i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase::TrySubstitute method


Ersätter originalteckensnittet med ett annat teckensnitt.

```cpp
virtual bool Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute(System::SharedPtr<CustomFontSubstitutionBase::OriginalFontSpecification> originalFontSpecification, System::SharedPtr<Font> &substitutionFont)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originalFontSpecification | System::SharedPtr\<CustomFontSubstitutionBase::OriginalFontSpecification\> | Original teckensnittsspecifikation. |
| substitutionFont | System::SharedPtr\<Font\>\& | Ersättningsteckensnitt. |

### ReturnValue

Sant om ersättningen lyckades.
## Anmärkningar


Klassen [CustomFontSubstitutionBase](../) bör ärvas för att implementera anpassad logik för teckensnittsersättning. Metoden TrySubstitute bör åsidosättas korrekt:

Måste returnera true om ersättning krävs. substitutionFont måste sättas till ett giltigt [Font](../../font/)‑objekt. Måste returnera false om ingen ersättning krävs. substitutionFont kan sättas till null.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OriginalFontSpecification](../originalfontspecification/)
* Class [Font](../../font/)
* Class [CustomFontSubstitutionBase](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
