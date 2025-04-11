---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfAOptionsBase. Obtient ou définit la stratégie de suppression des polices pour minimiser la taille du fichier de sortie lors du processus de conversion PDF/A
type: docs
weight: 30
url: /fr/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## Propriété PdfAOptionsBase.ExcludeFontsStrategy

Obtient ou définit la stratégie de suppression des polices pour minimiser la taille du fichier de sortie lors du processus de conversion PDF/A.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Valeur de la Propriété

La stratégie de suppression des polices. Cela peut être l'une des valeurs de l'énumération [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/). La valeur par défaut est la combinaison de SubsetFonts et RemoveDuplicatedFonts.

## Remarques

Cette propriété vous permet de contrôler comment les polices sont gérées pendant le processus de conversion. Vous pouvez choisir de supprimer les polices dupliquées, de supprimer les polices similaires avec des largeurs différentes, ou de sous-ensemble des polices.

### Voir Aussi

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)