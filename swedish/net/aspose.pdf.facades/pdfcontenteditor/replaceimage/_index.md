---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Ersätter den angivna bilden på den angivna sidan av PDF-dokumentet med en annan bild
type: docs
weight: 440
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage metod

Ersätter den angivna bilden på den angivna sidan av PDF-dokumentet med en annan bild.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Numret på sidan där bilden ersätts. |
| index | Int32 | Indexet för bildobjektet som måste ersättas. |
| imageFile | String | Bildfilen som kommer att användas för att ersätta. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)