---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق ختم مطاطي
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

تنشئ تعليق ختم مطاطي.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| annotRect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| icon | String | أيقونة سيتم استخدامها في عرض التعليق. القيمة الافتراضية: 'مسودة'. |
| annotContents | String | محتويات التعليق. |
| color | Color | لون التعليق. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

تنشئ تعليق ختم مطاطي.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| annotRect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| annotContents | String | محتويات التعليق. |
| color | Color | لون التعليق. |
| appearanceFile | String | مسار ملف المظهر. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

تنشئ تعليق ختم مطاطي.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| annotRect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| annotContents | String | محتويات التعليق. |
| color | Color | لون التعليق. |
| appearanceStream | Stream | تدفق ملف المظهر. |

## Examples

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)