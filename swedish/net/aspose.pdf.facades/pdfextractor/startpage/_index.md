---
title: "PdfExtractor.StartPage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor-egenskap. Hämtar eller anger startsida i sidintervallet där extraheringsoperationen kommer att utföras"
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

Hämtar eller anger startsidan i sidintervallet där extraheringsoperationen kommer att utföras.

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

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


