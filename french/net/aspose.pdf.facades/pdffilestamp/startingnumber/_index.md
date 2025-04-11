---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfFileStamp. Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est défini sur 100, les pages du document auront les numéros 100, 101, 102
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## Propriété PdfFileStamp.StartingNumber

Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est défini sur 100, les pages du document auront les numéros 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Voir aussi

* classe [PdfFileStamp](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)