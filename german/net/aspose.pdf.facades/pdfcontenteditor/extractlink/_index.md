---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Extrahiert die Sammlung von Link-Instanzen, die im PDF-Dokument enthalten sind
type: docs
weight: 370
url: /de/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink-Methode

Extrahiert die Sammlung von Link-Instanzen, die im PDF-Dokument enthalten sind.

```csharp
public IList<Annotation> ExtractLink()
```

### Rückgabewert

Die Sammlung von Link-Objekten

## Beispiele

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

### Siehe auch

* Klasse [Annotation](../../../aspose.pdf.annotations/annotation/)
* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)