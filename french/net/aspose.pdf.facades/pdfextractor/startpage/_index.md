---
title: "PdfExtractor.StartPage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfExtractor. Obtient ou définit la page de début dans la plage de pages où l'opération d'extraction sera effectuée"
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

Obtient ou définit la page de début dans la plage de pages où l'opération d'extraction sera effectuée.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


