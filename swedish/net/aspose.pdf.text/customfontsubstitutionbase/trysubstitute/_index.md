---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: CustomFontSubstitutionBase-metod. Ersätter originaltypsnitt med ett annat typsnitt
type: docs
weight: 20
url: /sv/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute metod

Ersätter originaltypsnitt med ett annat typsnitt.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Specifikation för originaltypsnitt. |
| substitutionFont | Font& | Ersättningstypografi. |

### Returvärde

Sant om ersättningen var framgångsrik.

## Kommentarer

Klassen CustomFontSubstitutionBase bör ärvas för att implementera anpassad logik för typsnittsersättning. TrySubstitute-metoden bör åsidosättas korrekt: Måste returnera sant om ersättning krävs. substitutionFont måste sättas till ett giltigt Font-objekt. Måste returnera falskt om ingen ersättning krävs. substitutionFont kan sättas till null.

### Se Även

* klass [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* klass [Font](../../font/)
* klass [CustomFontSubstitutionBase](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)