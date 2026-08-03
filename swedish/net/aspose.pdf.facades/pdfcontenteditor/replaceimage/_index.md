---
title: "PdfContentEditor.ReplaceImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Ersätter den angivna bilden på den angivna sidan i PDF-dokumentet med en annan bild"
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
| pageNumber | Int32 | Numret på sidan där bilden ersätts. |
| index | Int32 | Indexet för bildobjektet som ska ersättas. |
| imageFile | String | Bildfilen kommer att användas för ersättning. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


