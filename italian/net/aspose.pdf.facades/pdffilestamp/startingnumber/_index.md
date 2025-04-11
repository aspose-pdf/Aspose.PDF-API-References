---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfFileStamp. Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. Ad esempio, se il numero iniziale è impostato su 100, le pagine del documento avranno i numeri 100, 101, 102
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## Proprietà PdfFileStamp.StartingNumber

Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. Ad esempio, se il numero iniziale è impostato su 100, le pagine del documento avranno i numeri 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Vedi Anche

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)