---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfExtractor. Obtient ou définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée
type: docs
weight: 20
url: /fr/net/aspose.pdf.facades/pdfextractor/endpage/
---
## Propriété PdfExtractor.EndPage

Obtient ou définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)