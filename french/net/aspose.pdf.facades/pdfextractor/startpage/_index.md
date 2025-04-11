---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfExtractor. Obtient ou définit la page de départ dans la plage de pages où l'opération d'extraction sera effectuée
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/pdfextractor/startpage/
---
## Propriété PdfExtractor.StartPage

Obtient ou définit la page de départ dans la plage de pages où l'opération d'extraction sera effectuée.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)