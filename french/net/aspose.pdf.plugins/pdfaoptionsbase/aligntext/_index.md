---
title: "PdfAOptionsBase.AlignText"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfAOptionsBase. Obtient ou définit une valeur indiquant si des moyens supplémentaires sont nécessaires pour préserver l'alignement du texte pendant le processus de conversion PDF/A."
type: docs
weight: 10
url: /fr/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

Obtient ou définit une valeur indiquant si des moyens supplémentaires sont nécessaires pour préserver l'alignement du texte pendant le processus de conversion PDF/A.

```csharp
public bool AlignText { get; set; }
```

### Property Value

`true` si l'alignement du texte est modifié et que des actions supplémentaires sont nécessaires pour le restaurer ; sinon, `false`.

## Remarques

Lorsque la valeur est `true`, le processus de conversion tentera de restaurer les limites originales des segments de texte. Pour la plupart des documents, il n'est pas nécessaire de modifier cette propriété de la valeur par défaut `false`, car l'alignement du texte ne change pas pendant le processus de conversion par défaut.

### Voir aussi

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


