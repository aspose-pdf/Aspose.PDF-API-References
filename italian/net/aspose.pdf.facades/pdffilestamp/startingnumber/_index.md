---
title: "PdfFileStamp.StartingNumber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfFileStamp property. Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. Per esempio, se StartingNumber è impostato a 100 le pagine del documento avranno i numeri 100 101 102."
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

Ottiene o imposta il numero iniziale per la prima page nel file di input. Le pagine successive saranno numerate a partire da questo valore. Ad esempio, se StartingNumber è impostato a 100, le pagine del document avranno i numeri 100, 101, 102...

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

### Vedi anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


