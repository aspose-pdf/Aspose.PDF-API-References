---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Aspose.PDF för .NET API‑referens"
description: "CustomFontSubstitutionBase metod. Ersätter originalteckensnitt med ett annat teckensnitt"
type: docs
weight: 20
url: /sv/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

Ersätter originalteckensnittet med ett annat teckensnitt.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Original teckensnittsspecifikation. |
| substitutionFont | Font& | Ersättningsteckensnitt. |

### Returvärde

Sant om ersättningen lyckades.

## Anmärkningar

Klassen CustomFontSubstitutionBase bör ärvas för att implementera anpassad teckensnittsersättningslogik. Metoden TrySubstitute bör åsidosättas korrekt: Måste returnera true om ersättning krävs. substitutionFont måste sättas till ett giltigt Font-objekt. Måste returnera false om ingen ersättning krävs. substitutionFont kan sättas till null.

### Se även

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


