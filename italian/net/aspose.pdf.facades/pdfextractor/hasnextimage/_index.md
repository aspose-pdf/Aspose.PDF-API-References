---
title: "PdfExtractor.HasNextImage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfExtractor. Verifica se sono disponibili altre immagini nel documento PDF. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo"
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

Verifica se sono disponibili altre immagini nel documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo.

```csharp
public bool HasNextImage()
```

### Valore di ritorno

True se sono disponibili più immagini

## Esempi

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


