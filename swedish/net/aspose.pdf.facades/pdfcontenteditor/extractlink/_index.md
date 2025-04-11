---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Extraherar samlingen av Link-instansar som finns i PDF-dokumentet
type: docs
weight: 370
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink metod

Extraherar samlingen av Link-instansar som finns i PDF-dokumentet.

```csharp
public IList<Annotation> ExtractLink()
```

### Returvärde

Samlingen av Link-objekt

## Exempel

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

### Se Även

* klass [Annotation](../../../aspose.pdf.annotations/annotation/)
* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)