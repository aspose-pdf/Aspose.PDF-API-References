---
title: "PdfFileStamp.StartingNumber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileStamp-egenskap. Hämtar eller anger startnummer för den första sidan i indatafilen. Efterföljande sidor numreras med början från detta värde. Till exempel, om StartingNumber är satt till 100 kommer dokumentets sidor ha nummer 100 101 102"
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

Hämtar eller anger startnummer för den första sidan i indatafilen. Efterföljande sidor kommer att numreras med början från detta värde. Till exempel, om StartingNumber är satt till 100, kommer dokumentets sidor att ha nummer 100, 101, 102...

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

### Se även

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


