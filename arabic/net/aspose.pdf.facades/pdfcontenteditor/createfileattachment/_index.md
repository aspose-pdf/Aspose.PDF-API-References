---
title: CreateFileAttachment
second_title: Aspose.PDF لمرجع .NET API
description: إنشاء تعليق توضيحي لمرفق الملف .
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

إنشاء تعليق توضيحي لمرفق الملف .

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق التوضيحي الذي يحدد موقع التعليق التوضيحي على الصفحة. |
| contents | String | محتويات الشرح. |
| filePath | String | سيتم إرفاق مسار الملف. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق التوضيحي. |
| name | String | سيتم استخدام اسم الرمز في عرض التعليق التوضيحي . يمكن أن تكون هذه القيمة: "رسم بياني" ، "PushPin" ، "مشبك ورق" ، "علامة". |

### أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

إنشاء تعليق توضيحي لمرفق الملف .

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق التوضيحي الذي يحدد موقع التعليق التوضيحي على الصفحة. |
| contents | String | محتويات الشرح. |
| filePath | String | سيتم إرفاق مسار الملف. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق التوضيحي. |
| name | String | سيتم استخدام اسم الرمز في عرض التعليق التوضيحي . يمكن أن تكون هذه القيمة: "رسم بياني" ، "PushPin" ، "مشبك ورق" ، "علامة". |
| opacity | Double | تعتيم الرمز من 0 إلى 1: 0 - شفاف تمامًا ، 1 - معتم تمامًا. |

### أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

إنشاء تعليق توضيحي لمرفق الملف .

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق التوضيحي الذي يحدد موقع التعليق التوضيحي على الصفحة. |
| contents | String | محتويات الشرح. |
| attachmentStream | Stream | تدفق ملف المرفق. |
| attachmentName | String | اسم المرفق. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق التوضيحي. |
| name | String | سيتم استخدام اسم الرمز في عرض التعليق التوضيحي . يمكن أن تكون هذه القيمة: "رسم بياني" ، "PushPin" ، "مشبك ورق" ، "علامة". |

### أمثلة

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

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

إنشاء تعليق توضيحي لمرفق الملف .

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق التوضيحي الذي يحدد موقع التعليق التوضيحي على الصفحة. |
| contents | String | محتويات الشرح. |
| attachmentStream | Stream | تدفق ملف المرفق. |
| attachmentName | String | اسم المرفق. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق التوضيحي. |
| name | String | سيتم استخدام اسم الرمز في عرض التعليق التوضيحي . يمكن أن تكون هذه القيمة: "رسم بياني" ، "PushPin" ، "مشبك ورق" ، "علامة". |
| opacity | Double | تعتيم الرمز من 0 إلى 1: 0 - شفاف تمامًا ، 1 - معتم تمامًا. |

### أمثلة

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

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
