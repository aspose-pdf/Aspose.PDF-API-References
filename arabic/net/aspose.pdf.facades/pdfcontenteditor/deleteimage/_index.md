---
title: "PdfContentEditor.DeleteImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تحذف الصور المحددة في الصفحة المحددة."
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

يحذف الصور المحددة في الصفحة المحددة.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي يجب حذف الصور منها. |
| index | Int32[] | مصفوفة تمثل فهارس الصور. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

يحذف جميع الصور من مستند PDF.

```csharp
public void DeleteImage()
```

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


