---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تعيد حجم محتويات الصفحة وتضيف الهوامش المحددة. يتم تحديد الهوامش بوحدات الفضاء الافتراضية
type: docs
weight: 220
url: /ar/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

تعيد حجم محتويات الصفحة وتضيف الهوامش المحددة. يتم تحديد الهوامش بوحدات الفضاء الافتراضية.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | التدفق الذي يحتوي على الوثيقة المصدر. |
| destination | Stream | التدفق الذي سيتم حفظ الوثيقة الناتجة فيه. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| leftMargin | Double | الهامش الأيسر. |
| rightMargin | Double | الهامش الأيمن. |
| topMargin | Double | الهامش العلوي. |
| bottomMargin | Double | الهامش السفلي. |

### Return Value

true إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

تعيد حجم محتويات الصفحة وتضيف الهوامش المحددة. يتم تحديد الهوامش بوحدات الفضاء الافتراضية.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | المسار إلى الوثيقة المصدر. |
| destination | String | المسار الذي سيتم حفظ الوثيقة الناتجة فيه. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| leftMargin | Double | الهامش الأيسر. |
| rightMargin | Double | الهامش الأيمن. |
| topMargin | Double | الهامش العلوي. |
| bottomMargin | Double | الهامش السفلي. |

### Return Value

true إذا كان تغيير الحجم ناجحًا.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)