---
title: PdfToDocOptions.ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfToDocOptions. Permet de contrôler comment un document PDF est converti en un document de traitement de texte
type: docs
weight: 20
url: /fr/net/aspose.pdf.plugins/pdftodocoptions/conversionmode/
---
## Propriété PdfToDocOptions.ConversionMode

Permet de contrôler comment un document PDF est converti en un document de traitement de texte.

```csharp
public ConversionMode ConversionMode { get; set; }
```

## Remarques

Utilisez le mode TextBox lorsque le document résultant ne sera pas beaucoup modifié par la suite. Les zones de texte sont faciles à modifier lorsqu'il n'y a pas beaucoup à faire.

Utilisez le mode Flow lorsque le document de sortie nécessite des modifications supplémentaires. Les paragraphes et les lignes de texte en mode flow permettent une modification facile du texte, mais les objets de formatage non pris en charge auront un aspect moins bon qu'en mode TextBox.

### Voir aussi

* enum [ConversionMode](../../conversionmode/)
* class [PdfToDocOptions](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)