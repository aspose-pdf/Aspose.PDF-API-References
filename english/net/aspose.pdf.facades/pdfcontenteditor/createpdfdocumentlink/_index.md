---
title: "PdfContentEditor.CreatePdfDocumentLink"
linktitle: "CreatePdfDocumentLink"
articleTitle: "CreatePdfDocumentLink"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates a link to another PDF document page."
type: docs
weight: 110
url: "/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/"
product_version: "26.9.0"
---
## CreatePdfDocumentLink([Rectangle](../../../aspose.pdf.drawing/rectangle/), string, int, int, [Color](../../../aspose.pdf/color/), Enum[]) {#createpdfdocumentlink}

Creates a link to another PDF document page.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| remotePdf | String | The PDF document which page will be opened. |
| originalPage | Int32 | The number of original page where rectangle bound with link will be created. |
| destinationPage | Int32 | The destination page. |
| clr | Color | The colour of rectangle for active click. |
| actionName | Enum[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [Color](../../../aspose.pdf/color/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink([Rectangle](../../../aspose.pdf.drawing/rectangle/), string, int, int, [Color](../../../aspose.pdf/color/)) {#createpdfdocumentlink_1}

Creates a link to another PDF document page.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| remotePdf | String | The PDF document which page will be opened. |
| originalPage | Int32 | The number of original page where rectangle bound with link will be created. |
| destinationPage | Int32 | The destination page. |
| clr | Color | The colour of rectangle for active click. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [Color](../../../aspose.pdf/color/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink([Rectangle](../../../aspose.pdf.drawing/rectangle/), string, int, int) {#createpdfdocumentlink_2}

Creates a link to another PDF document page.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| remotePdf | String | The PDF document which page will be opened. |
| originalPage | Int32 | The number of original page where rectangle bound with link will be created. |
| destinationPage | Int32 | The destination page. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

