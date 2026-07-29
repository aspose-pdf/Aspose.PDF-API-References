---
title: "PdfContentEditor.DeleteStampById"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تحذف الختم في الصفحة المحددة بواسطة معرف الختم"
type: docs
weight: 340
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

يحذف الطابع في الصفحة المحددة حسب معرف الطابع.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي سيتم حذف الختم منها. |
| stampId | Int32 | معرف الطابع الذي يجب حذفه. |

## أمثلة

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

احذف الطابع حسب المعرف من جميع صفحات المستند.

```csharp
public void DeleteStampById(int stampId)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stampId | Int32 | معرف الختم الذي يجب حذفه. |

## أمثلة

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


