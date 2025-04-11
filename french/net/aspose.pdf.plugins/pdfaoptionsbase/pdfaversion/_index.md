---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfAOptionsBase. Obtient ou définit la version de la norme PDF/A à utiliser pour la validation ou la conversion
type: docs
weight: 110
url: /fr/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## Propriété PdfAOptionsBase.PdfAVersion

Obtient ou définit la version de la norme PDF/A à utiliser pour la validation ou la conversion.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Valeur de la propriété

La version de la norme PDF/A. Cela peut être l'une des valeurs de l'énumération [`PdfAStandardVersion`](../../pdfastandardversion/).

## Remarques

La version de la norme PDF/A est utilisée pour déterminer le niveau de conformité pour la validation et la conversion PDF/A. Si la version est définie sur Auto, le système déterminera automatiquement la version de la norme PDF/A appropriée pour la validation en fonction des métadonnées du document. Pour le processus de conversion PDF/A, l'option Auto par défaut est la version de la norme PDF/A-1b.

### Voir aussi

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)