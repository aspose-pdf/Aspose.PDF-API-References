---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تحذف الصور المحددة في الصفحة المحددة
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

تحذف الصور المحددة في الصفحة المحددة.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي يجب حذف الصور منها. |
| index | Int32[] | مصفوفة تمثل فهارس الصور. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

تحذف جميع الصور من مستند PDF.

```csharp
public void DeleteImage()
```

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)