---
title: "Document.EmbedStandardFonts"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Document property. Propriété qui indique que le document doit incorporer toutes les polices standard Type1 dont le drapeau IsEmbedded est réglé sur true. Toutes les polices PDF peuvent être incorporées dans le document simplement en réglant le drapeau IsEmbedded sur true, mais les polices standard Type1 du PDF sont une exception à cette règle. L’incorporation des polices Type1 standard prend beaucoup de temps, il est donc nécessaire non seulement de régler le drapeau IsEmbedded sur true pour la police spécifiée, mais aussi de définir un drapeau supplémentaire au niveau du document : EmbedStandardFonts true. Cette propriété ne peut être définie qu’une seule fois pour toutes les polices. Par défaut false."
type: docs
weight: 160
url: /fr/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts property

Propriété qui indique que le document doit incorporer toutes les polices standard Type1 dont le drapeau IsEmbedded est réglé sur true. Toutes les polices PDF peuvent être incorporées dans le document simplement en définissant le drapeau IsEmbedded sur true, mais les polices standard Type1 du PDF sont une exception à cette règle. L'incorporation des polices Type1 standard nécessite beaucoup de temps, il faut donc non seulement régler le drapeau IsEmbedded sur true pour la police spécifiée, mais aussi définir un drapeau supplémentaire au niveau du document – EmbedStandardFonts = true ; Cette propriété ne peut être définie qu'une seule fois pour toutes les polices. Par défaut false.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


