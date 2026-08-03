---
title: "PdfExtractor.GetAttachNames"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor-metod. Returnerar en lista över bilagor i PDF-filen. Observera att ExtractAttachments måste anropas innan denna metod används"
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

Returnerar en lista över bilagor i PDF-filen. Obs: ExtractAttachments måste anropas innan denna metod används.

```csharp
public IList<string> GetAttachNames()
```

### Returvärde

Lista över bilagor

## Exempel

Exemplet visar hur man extraherar namn på bilagor från PDF-filen.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


