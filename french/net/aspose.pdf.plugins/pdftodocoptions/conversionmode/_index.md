---
title: "PdfToDocOptions.ConversionMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfToDocOptions. Permet de contrôler comment un document PDF est converti en document de traitement de texte"
type: docs
weight: 20
url: /fr/net/aspose.pdf.plugins/pdftodocoptions/conversionmode/
---
## PdfToDocOptions.ConversionMode property

Permet de contrôler comment un document PDF est converti en document de traitement de texte.

```csharp
public ConversionMode ConversionMode { get; set; }
```

## Remarques

Utilisez le mode TextBox lorsque le document résultant ne sera pas fortement modifié par la suite. Les Textboxes sont faciles à modifier lorsqu'il n'y a pas grand-chose à faire.

Utilisez le mode Flow lorsque le document de sortie nécessite une édition supplémentaire. Les paragraphes et les lignes de texte en mode Flow permettent une modification facile du texte, mais les objets de formatage non pris en charge auront un rendu pire que dans le mode TextBox.

### Voir aussi

* enum [ConversionMode](../../conversionmode/)
* class [PdfToDocOptions](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


