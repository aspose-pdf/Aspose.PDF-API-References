---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Ersetzt das angegebene Bild auf der angegebenen Seite des PDF-Dokuments durch ein anderes Bild
type: docs
weight: 440
url: /de/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage-Methode

Ersetzt das angegebene Bild auf der angegebenen Seite des PDF-Dokuments durch ein anderes Bild.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Nummer der Seite, auf der das Bild ersetzt wird. |
| index | Int32 | Der Index des Bildobjekts, das ersetzt werden muss. |
| imageFile | String | Die Bilddatei, die zum Ersetzen verwendet wird. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)