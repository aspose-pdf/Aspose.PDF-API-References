---
title: "PdfContentEditor.ExtractLink"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Extraherar samlingen av Link-objekt som finns i PDF-dokumentet"
type: docs
weight: 370
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Extraherar samlingen av Link-instanser som finns i PDF-dokument.

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
    // arbeta med Link-instans
}
```

### Se även

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


