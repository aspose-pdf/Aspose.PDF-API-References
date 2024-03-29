---
title: ReplaceImage
second_title: Aspose.PDF för .NET API Referens
description: Ersätter den angivna bilden på den angivna sidan i PDF-dokumentet med en annan bild.
type: docs
weight: 440
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

Ersätter den angivna bilden på den angivna sidan i PDF-dokumentet med en annan bild.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Antalet sidor där bilden ersätts. |
| index | Int32 | Bildobjektets index måste bytas ut. |
| imageFile | String | Bildfilen kommer att användas för att ersätta. |

### Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
