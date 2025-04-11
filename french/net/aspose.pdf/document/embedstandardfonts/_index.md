---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: Propriété du document. Propriété qui déclare que le document doit intégrer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai. Toutes les polices PDF peuvent être intégrées dans le document simplement en définissant le drapeau IsEmbedded sur vrai, mais les polices Type1 standard PDF sont une exception à cette règle. L'intégration des polices Type1 standard nécessite beaucoup de temps, donc pour intégrer ces polices, il est nécessaire non seulement de définir le drapeau IsEmbedded sur vrai pour la police spécifiée, mais aussi de définir un drapeau supplémentaire au niveau du document - EmbedStandardFonts = vrai ; Cette propriété ne peut être définie qu'une seule fois pour toutes les polices. Par défaut faux.
type: docs
weight: 150
url: /fr/net/aspose.pdf/document/embedstandardfonts/
---
## Propriété Document.EmbedStandardFonts

Propriété qui déclare que le document doit intégrer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai. Toutes les polices PDF peuvent être intégrées dans le document simplement en définissant le drapeau IsEmbedded sur vrai, mais les polices Type1 standard PDF sont une exception à cette règle. L'intégration des polices Type1 standard nécessite beaucoup de temps, donc pour intégrer ces polices, il est nécessaire non seulement de définir le drapeau IsEmbedded sur vrai pour la police spécifiée, mais aussi de définir un drapeau supplémentaire au niveau du document - EmbedStandardFonts = vrai ; Cette propriété ne peut être définie qu'une seule fois pour toutes les polices. Par défaut faux.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)