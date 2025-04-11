---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-egenskap. Hämtar eller ställer in startnummer för första sidan i indatafilen. Nästa sidor kommer att numreras från detta värde. Till exempel, om StartingNumber är inställt på 100, kommer dokumentets sidor att ha nummer 100, 101, 102
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber-egenskap

Hämtar eller ställer in startnummer för första sidan i indatafilen. Nästa sidor kommer att numreras från detta värde. Till exempel, om StartingNumber är inställt på 100, kommer dokumentets sidor att ha nummer 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)