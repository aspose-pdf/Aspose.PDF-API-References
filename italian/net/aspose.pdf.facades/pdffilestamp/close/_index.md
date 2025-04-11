---
title: PdfFileStamp.Close
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileStamp. Chiude i file aperti e salva le modifiche. Attenzione. Se i flussi di input o output sono specificati, non vengono chiusi dal metodo Close
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/pdffilestamp/close/
---
## Metodo PdfFileStamp.Close

Chiude i file aperti e salva le modifiche. Attenzione. Se i flussi di input o output sono specificati, non vengono chiusi dal metodo Close().

```csharp
public override void Close()
```

## Esempi

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
//do some work... 
stamp.Close();
```

### Vedi Anche

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)