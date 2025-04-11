---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfExtractor. Définit le mode pour le résultat de l'extraction de textes
type: docs
weight: 40
url: /fr/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## Propriété PdfExtractor.ExtractTextMode

Définit le mode pour le résultat de l'extraction de texte.

```csharp
public int ExtractTextMode { get; set; }
```

### Valeur de la Propriété

0 est le mode texte pur et 1 est le mode d'ordre brut. Par défaut, c'est 0.

## Exemples

L'exemple démontre l'utilisation de la propriété `ExtractTextMode` dans un scénario d'extraction de texte.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Voir Aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)