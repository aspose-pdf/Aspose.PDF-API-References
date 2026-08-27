---
title: "PdfContentEditor.ExtractLink"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Estrae la collezione di istanze Link contenute nel documento PDF"
type: docs
weight: 370
url: /it/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Estrae la raccolta di istanze Link contenute nel documento PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Valore di ritorno

La collezione di oggetti Link

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // lavorare con l'istanza Link
}
```

### Vedi anche

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


