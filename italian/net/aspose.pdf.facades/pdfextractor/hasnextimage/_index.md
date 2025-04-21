---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfExtractor. Controlla se ci sono altre immagini accessibili nel documento PDF. Nota ExtractImage deve essere chiamato prima di utilizzare questo metodo
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## Metodo PdfExtractor.HasNextImage

Controlla se ci sono altre immagini accessibili nel documento PDF. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo.

```csharp
public bool HasNextImage()
```

### Valore di Ritorno

Vero se ci sono altre immagini accessibili

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

### Vedi Anche

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)