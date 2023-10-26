---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Replaces the specified image on the specified page of PDF document with another image
type: docs
weight: 440
url: /net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

Replaces the specified image on the specified page of PDF document with another image.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | The number of page on which the image is replaced. |
| index | Int32 | The index of the image object must be replaced. |
| imageFile | String | The image file will be used for replacing. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


