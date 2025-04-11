---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تعيد حجم محتويات الصفحة وتضيف الهوامش المحددة. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأولي
type: docs
weight: 230
url: /ar/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

تعيد حجم محتويات الصفحة وتضيف الهوامش المحددة. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأولي.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | التدفق الذي يحتوي على الوثيقة المصدر. |
| destination | Stream | التدفق الذي سيتم حفظ الوثيقة الناتجة فيه. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| leftMargin | Double | الهامش الأيسر كنسبة مئوية من حجم الصفحة الأولي. |
| rightMargin | Double | الهامش الأيمن كنسبة مئوية من حجم الصفحة الأولي. |
| topMargin | Double | الهامش العلوي كنسبة مئوية من حجم الصفحة الأولي. |
| bottomMargin | Double | الهامش السفلي كنسبة مئوية من حجم الصفحة الأولي. |

### Return Value

true إذا تم تنفيذ الإجراء بنجاح.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

تعيد حجم محتويات الصفحة وتضيف الهوامش المحددة. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأولي.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | المسار إلى الوثيقة المصدر. |
| destination | String | المسار الذي سيتم حفظ الوثيقة الناتجة فيه. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| leftMargin | Double | الهامش الأيسر كنسبة مئوية من حجم الصفحة الأولي. |
| rightMargin | Double | الهامش الأيمن كنسبة مئوية من حجم الصفحة الأولي. |
| topMargin | Double | الهامش العلوي كنسبة مئوية من حجم الصفحة الأولي. |
| bottomMargin | Double | الهامش السفلي كنسبة مئوية من حجم الصفحة الأولي. |

### Return Value

true إذا كان تغيير الحجم ناجحاً

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)