---
title: "PdfContentEditor.CreateFileAttachment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تُنشئ توضيح مرفق ملف"
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

ينشئ تعليقة مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| filePath | String | سيتم إرفاق مسار الملف. |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| الاسم | String | سيتم استخدام اسم أيقونة في عرض التوضيح. يمكن أن تكون هذه القيمة: "Graph", "PushPin", "Paperclip", "Tag". |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

ينشئ تعليقة مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| filePath | String | سيتم إرفاق مسار الملف. |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| الاسم | String | سيتم استخدام اسم أيقونة في عرض التوضيح. يمكن أن تكون هذه القيمة: "Graph", "PushPin", "Paperclip", "Tag". |
| العتامة | Double | عتامة الأيقونة من 0 إلى 1: 0 - شفافة تمامًا، 1 - غير شفافة تمامًا. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

ينشئ تعليقة مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| attachmentStream | Stream | دفق ملف المرفق. |
| attachmentName | String | اسم المرفق. |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| الاسم | String | سيتم استخدام اسم أيقونة في عرض التوضيح. يمكن أن تكون هذه القيمة: "Graph", "PushPin", "Paperclip", "Tag". |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

ينشئ تعليقة مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| attachmentStream | Stream | دفق ملف المرفق. |
| attachmentName | String | اسم المرفق. |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| الاسم | String | سيتم استخدام اسم أيقونة في عرض التوضيح. يمكن أن تكون هذه القيمة: "Graph", "PushPin", "Paperclip", "Tag". |
| العتامة | Double | عتامة الأيقونة من 0 إلى 1: 0 - شفافة تمامًا، 1 - غير شفافة تمامًا. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


