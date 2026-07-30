---
title: "PdfExtractor.EndPage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfExtractor. Obtient ou définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée."
type: docs
weight: 20
url: /fr/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


