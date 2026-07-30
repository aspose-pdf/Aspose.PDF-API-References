---
title: "PdfExtractor.ExtractTextMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfExtractor. Définit le mode du résultat d'extraction de texte."
type: docs
weight: 40
url: /fr/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

Définit le mode du résultat d'extraction de texte.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 correspond au mode texte pur et 1 au mode ordre brut. La valeur par défaut est 0.

## Exemples

L'exemple montre l'utilisation de la propriété `ExtractTextMode` dans un scénario d'extraction de texte.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Voir aussi

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


