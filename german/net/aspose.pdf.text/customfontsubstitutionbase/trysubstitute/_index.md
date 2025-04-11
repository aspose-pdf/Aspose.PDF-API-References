---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: CustomFontSubstitutionBase-Methode. Ersetzt die ursprüngliche Schriftart durch eine andere Schriftart
type: docs
weight: 20
url: /de/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute-Methode

Ersetzt die ursprüngliche Schriftart durch eine andere Schriftart.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Spezifikation der ursprünglichen Schriftart. |
| substitutionFont | Font& | Ersatzschriftart. |

### Rückgabewert

True, falls die Ersetzung erfolgreich war.

## Anmerkungen

Die Klasse CustomFontSubstitutionBase sollte erweitert werden, um benutzerdefinierte Schriftart-Ersetzungslogik zu implementieren. Die Methode TrySubstitute sollte ordnungsgemäß überschrieben werden: Muss true zurückgeben, falls eine Ersetzung erforderlich ist. substitutionFont muss auf ein gültiges Font-Objekt gesetzt werden. Muss false zurückgeben, falls keine Ersetzung erforderlich ist. substitutionFont kann auf null gesetzt werden.

### Siehe auch

* Klasse [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* Klasse [Font](../../font/)
* Klasse [CustomFontSubstitutionBase](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)