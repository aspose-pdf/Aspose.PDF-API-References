---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfExtractor. Restituisce un elenco di allegati nel file PDF. Nota ExtractAttachments deve essere chiamato prima di utilizzare questo metodo
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## Metodo PdfExtractor.GetAttachNames

Restituisce un elenco di allegati nel file PDF. Nota: ExtractAttachments deve essere chiamato prima di utilizzare questo metodo.

```csharp
public IList<string> GetAttachNames()
```

### Valore di ritorno

Elenco di allegati

## Esempi

L'esempio dimostra come estrarre i nomi degli allegati da un file PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Vedi anche

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)