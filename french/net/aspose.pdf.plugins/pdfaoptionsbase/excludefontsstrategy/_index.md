---
title: "PdfAOptionsBase.ExcludeFontsStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfAOptionsBase. Obtient ou définit la stratégie de suppression des polices afin de réduire la taille du fichier de sortie pendant le processus de conversion PDF/A."
type: docs
weight: 30
url: /fr/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy property

Obtient ou définit la stratégie de suppression des polices afin de réduire la taille du fichier de sortie pendant le processus de conversion PDF/A.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value

La stratégie de suppression des polices. Elle peut être l'une des valeurs de l'énumération [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/). La valeur par défaut est la combinaison de SubsetFonts et RemoveDuplicatedFonts.

## Remarques

Cette propriété vous permet de contrôler la façon dont les polices sont gérées pendant le processus de conversion. Vous pouvez choisir de supprimer les polices dupliquées, de supprimer les polices similaires avec des largeurs différentes, ou de sous‑ensemble les polices.

### Voir aussi

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


