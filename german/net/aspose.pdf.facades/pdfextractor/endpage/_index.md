---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Eigenschaft. Ruft die Endseite im Seitenbereich ab oder legt sie fest, in dem die Extraktionsoperation durchgeführt wird
type: docs
weight: 20
url: /de/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage-Eigenschaft

Ruft die Endseite im Seitenbereich ab oder legt sie fest, in dem die Extraktionsoperation durchgeführt wird.

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

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)