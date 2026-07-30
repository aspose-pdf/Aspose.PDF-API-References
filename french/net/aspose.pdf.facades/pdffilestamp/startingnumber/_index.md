---
title: "PdfFileStamp.StartingNumber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfFileStamp. Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est fixé à 100, les pages du document auront les numéros 100 101 102"
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est fixé à 100, les pages du document auront les numéros 100, 101, 102...

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

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


