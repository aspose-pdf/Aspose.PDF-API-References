---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-metod. Returnerar lista över bilagor i PDF-fil. Observera att ExtractAttachments måste anropas innan denna metod används
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames metod

Returnerar lista över bilagor i PDF-fil. Observera: ExtractAttachments måste anropas innan denna metod används.

```csharp
public IList<string> GetAttachNames()
```

### Returvärde

Lista över bilagor

## Exempel

Exemplet visar hur man extraherar bilagnamn från PDF-fil.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)