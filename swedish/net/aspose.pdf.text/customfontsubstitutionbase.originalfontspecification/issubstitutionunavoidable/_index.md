---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: OriginalFontSpecification-egenskap. Hämtar ett värde som indikerar att substitutionen är oundviklig
type: docs
weight: 20
url: /sv/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable-egenskap

Hämtar ett värde som indikerar att substitutionen är oundviklig.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Kommentarer

Returnerar true om substitution begärdes på grund av avsaknad av det ursprungliga typsnittet eller om det ursprungliga typsnittet inte kan användas i samband med en viss uppgift. Om användaren ignorerar flaggan och inte substituerar typsnittet - utförs standardproceduren för typsnittsubstitution. Men det ger användaren möjlighet att alternera standardproceduren för typsnittsubstitution och ställa in ett bättre typsnitt i systemet. Returnerar false om det ursprungliga typsnittet är närvarande, giltigt, men det är tillåtet för användaren att substituera det.

### Se Även

* klass [OriginalFontSpecification](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)