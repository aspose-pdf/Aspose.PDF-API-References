---
title: "PdfExtractor.EndPage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor-egenskap. Hämtar eller anger slutsida i sidintervallet där extraheringsoperationen ska utföras."
type: docs
weight: 20
url: /sv/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

Hämtar eller anger sista sidan i sidintervallet där extraheringsoperationen kommer att utföras.

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

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


