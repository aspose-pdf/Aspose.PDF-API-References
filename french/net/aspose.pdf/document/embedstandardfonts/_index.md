---
title: EmbedStandardFonts
second_title: Référence de l'API Aspose.PDF pour .NET
description: Propriété qui déclare que le document doit incorporer toutes les polices Type1 standard dont lindicateur IsEmbedded est défini sur true. Toutes les polices PDF peuvent être incorporées dans le document simplement via la définition de lindicateur IsEmbedded sur true mais les polices PDF standard Type1 sont une exception à cette règle. Lincorporation de polices Standard Type1 nécessite beaucoup de temps donc pour incorporer ces polices il est nécessaire non seulement de définir lindicateur Est intégré dans true pour la police spécifiée mais définit également un indicateur supplémentaire au niveau du document - EmbedStandardFonts  true Cette propriété ne peut être définie quune seule fois pour toutes les polices. Par défaut false.
type: docs
weight: 140
url: /fr/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts property

Propriété qui déclare que le document doit incorporer toutes les polices Type1 standard dont l'indicateur IsEmbedded est défini sur true. Toutes les polices PDF peuvent être incorporées dans le document simplement via la définition de l'indicateur IsEmbedded sur true, mais les polices PDF standard Type1 sont une exception à cette règle. L'incorporation de polices Standard Type1 nécessite beaucoup de temps, donc pour incorporer ces polices, il est nécessaire non seulement de définir l'indicateur Est intégré dans true pour la police spécifiée mais définit également un indicateur supplémentaire au niveau du document - EmbedStandardFonts = true; Cette propriété ne peut être définie qu'une seule fois pour toutes les polices. Par défaut false.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Voir également

* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->