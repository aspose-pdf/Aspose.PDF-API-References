---
title: "PdfExtractor.GetAttachNames"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfExtractor. Restituisce l'elenco degli allegati in un file PDF. Nota: ExtractAttachments deve essere chiamato prima di utilizzare questo metodo"
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

Restituisce l'elenco degli allegati nel file PDF. Nota: ExtractAttachments deve essere chiamato prima di utilizzare questo metodo.

```csharp
public IList<string> GetAttachNames()
```

### Valore di ritorno

Elenco degli allegati

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


