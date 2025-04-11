---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تحذف الختم في الصفحة المحددة بواسطة معرف الختم
type: docs
weight: 340
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

تحذف الختم في الصفحة المحددة بواسطة معرف الختم.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي سيتم حذف الختم منها. |
| stampId | Int32 | معرف الختم الذي يجب حذفه. |

## Examples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

احذف الختم بواسطة المعرف من جميع صفحات المستند.

```csharp
public void DeleteStampById(int stampId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stampId | Int32 | معرف الختم الذي يجب حذفه. |

## Examples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)