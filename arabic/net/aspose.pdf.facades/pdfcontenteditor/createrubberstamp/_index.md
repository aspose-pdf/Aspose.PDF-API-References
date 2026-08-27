---
title: "PdfContentEditor.CreateRubberStamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليق توضيحي بختم مطاطي"
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

ينشئ تعليقة ختم مطاطي.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| annotRect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| icon | String | يُستخدم أيقونة لعرض التعليق التوضيحي. القيمة الافتراضية: 'Draft'. |
| annotContents | String | محتوى التعليق التوضيحي. |
| color | Color | لون التعليق التوضيحي. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

ينشئ تعليقة ختم مطاطي.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| annotRect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| annotContents | String | محتوى التعليق التوضيحي. |
| color | Color | لون التعليق التوضيحي. |
| appearanceFile | String | مسار ملف المظهر. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

ينشئ تعليقة ختم مطاطي.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| annotRect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| annotContents | String | محتوى التعليق التوضيحي. |
| color | Color | لون التعليق التوضيحي. |
| appearanceStream | Stream | دفق ملف المظهر. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


