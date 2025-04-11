---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق مرفق ملف
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

تنشئ تعليق مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل التعليقي الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| filePath | String | مسار الملف الذي سيتم إرفاقه. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| name | String | اسم الرمز الذي سيتم استخدامه في عرض التعليق. يمكن أن تكون هذه القيمة: "Graph"، "PushPin"، "Paperclip"، "Tag". |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

تنشئ تعليق مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل التعليقي الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| filePath | String | مسار الملف الذي سيتم إرفاقه. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| name | String | اسم الرمز الذي سيتم استخدامه في عرض التعليق. يمكن أن تكون هذه القيمة: "Graph"، "PushPin"، "Paperclip"، "Tag". |
| opacity | Double | شفافية الرمز من 0 إلى 1: 0 - شفاف تمامًا، 1 - غير شفاف تمامًا. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

تنشئ تعليق مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل التعليقي الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| attachmentStream | Stream | تدفق ملف المرفق. |
| attachmentName | String | اسم المرفق. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| name | String | اسم الرمز الذي سيتم استخدامه في عرض التعليق. يمكن أن تكون هذه القيمة: "Graph"، "PushPin"، "Paperclip"، "Tag". |

## Examples

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

تنشئ تعليق مرفق ملف.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل التعليقي الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| attachmentStream | Stream | تدفق ملف المرفق. |
| attachmentName | String | اسم المرفق. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| name | String | اسم الرمز الذي سيتم استخدامه في عرض التعليق. يمكن أن تكون هذه القيمة: "Graph"، "PushPin"، "Paperclip"، "Tag". |
| opacity | Double | شفافية الرمز من 0 إلى 1: 0 - شفاف تمامًا، 1 - غير شفاف تمامًا. |

## Examples

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)