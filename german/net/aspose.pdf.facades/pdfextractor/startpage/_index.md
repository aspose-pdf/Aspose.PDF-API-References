---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Eigenschaft. Ruft die Startseite im Seitenbereich ab oder legt sie fest, in dem die Extraktionsoperation durchgeführt wird
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage-Eigenschaft

Ruft die Startseite im Seitenbereich ab oder legt sie fest, in dem die Extraktionsoperation durchgeführt wird.

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

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)