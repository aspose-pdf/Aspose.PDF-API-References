---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند."
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

يحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stampIds | Int32[] | مصفوفة من معرفات الطوابع. |

## أمثلة

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

يحذف الطوابع في الصفحة المحددة حسب عدة معرفات للطوابع.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي سيتم حذف الطوابع منها. |
| stampIds | Int32[] | مصفوفة من معرفات الطوابع. |

## أمثلة

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


