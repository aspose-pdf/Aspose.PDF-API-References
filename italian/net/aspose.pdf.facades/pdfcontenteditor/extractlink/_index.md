---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Extracts the collection of Link instances contained in PDF document
type: docs
weight: 370
url: /it/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## Metodo PdfContentEditor.ExtractLink

Estrae la collezione di istanze Link contenute nel documento PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Valore di Ritorno

La collezione di oggetti Link

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### Vedi Anche

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)