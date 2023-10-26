---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates a link to launch an application in PDF document
type: docs
weight: 110
url: /net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Creates a link to launch an application in PDF document.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| application | String | The path of application to be launched. |
| page | Int32 | The number of original page where rectangle bound with link will be created. |
| clr | Color | The colour of rectangle for active click. |
| actionName | Enum[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Creates a link to launch an application in PDF document.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| application | String | The path of application to be launched. |
| page | Int32 | The number of original page where rectangle bound with link will be created. |
| clr | Color | The colour of rectangle for active click. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Creates a link to launch an application in PDF document.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| application | String | The path of application to be launched. |
| page | Int32 | The number of original page where rectangle bound with link will be created. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


