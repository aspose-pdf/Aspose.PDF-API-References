---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfAOptionsBase. Obtient ou définit une valeur indiquant si des moyens supplémentaires sont nécessaires pour préserver l'alignement du texte pendant le processus de conversion PDF/A
type: docs
weight: 10
url: /fr/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## Propriété PdfAOptionsBase.AlignText

Obtient ou définit une valeur indiquant si des moyens supplémentaires sont nécessaires pour préserver l'alignement du texte pendant le processus de conversion PDF/A.

```csharp
public bool AlignText { get; set; }
```

### Valeur de la propriété

`true` si l'alignement du texte est modifié et que des actions supplémentaires sont nécessaires pour le restaurer ; sinon, `false`.

## Remarques

Lorsqu'il est défini sur `true`, le processus de conversion tentera de restaurer les limites du segment de texte original. Pour la plupart des documents, il n'est pas nécessaire de modifier cette propriété par rapport à la valeur par défaut `false`, car l'alignement du texte ne change pas pendant le processus de conversion par défaut.

### Voir aussi

* classe [PdfAOptionsBase](../)
* espace de noms [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)