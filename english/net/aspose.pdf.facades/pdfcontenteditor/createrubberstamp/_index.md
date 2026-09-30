---
title: "PdfContentEditor.CreateRubberStamp"
linktitle: "CreateRubberStamp"
articleTitle: "CreateRubberStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates a rubber stamp annotation."
type: docs
weight: 360
url: "/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/"
product_version: "26.9.0"
---
## CreateRubberStamp(int, [Rectangle](../../../aspose.pdf.drawing/rectangle/), string, string, [Color](../../../aspose.pdf/color/)) {#createrubberstamp}

Creates a rubber stamp annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| icon | String | An icon is to be used in displaying the annotation. Default value: 'Draft'. |
| annotContents | String | The contents of the annotation. |
| color | Color | The color of the annotation. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [Color](../../../aspose.pdf/color/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, [Rectangle](../../../aspose.pdf.drawing/rectangle/), string, [Color](../../../aspose.pdf/color/), string) {#createrubberstamp_1}

Creates a rubber stamp annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | String | The contents of the annotation. |
| color | Color | The colour of the annotation. |
| appearanceFile | String | The path of appearance file. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [Color](../../../aspose.pdf/color/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, [Rectangle](../../../aspose.pdf.drawing/rectangle/), string, [Color](../../../aspose.pdf/color/), Stream) {#createrubberstamp_2}

Creates a rubber stamp annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | String | The contents of the annotation. |
| color | Color | The colour of the annotation. |
| appearanceStream | Stream | The stream of appearance file. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}
```

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [Color](../../../aspose.pdf/color/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

