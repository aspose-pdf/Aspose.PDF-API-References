---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تعيد حجم محتويات صفحات الوثيقة. تقلص محتويات الصفحة وتضيف هوامش. يتم تحديد حجم المحتويات الجديدة كنسبة مئوية
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

تعيد حجم محتويات صفحات الوثيقة. تقلص محتويات الصفحة وتضيف هوامش. يتم تحديد حجم المحتويات الجديدة كنسبة مئوية.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | التدفق الذي يحتوي على الوثيقة المصدر. |
| destination | Stream | التدفق الذي سيتم حفظ الوثيقة الناتجة فيه. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة كنسبة مئوية. |
| newHeight | Double | الارتفاع الجديد لمحتويات الصفحة كنسبة مئوية. |

### Return Value

true إذا تم تغيير الحجم بنجاح.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

تعيد حجم محتويات صفحات الوثيقة. تقلص محتويات الصفحة وتضيف هوامش. يتم تحديد حجم المحتويات الجديدة كنسبة مئوية.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | المسار إلى الوثيقة المصدر. |
| destination | String | المسار الذي سيتم حفظ الوثيقة الناتجة فيه. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة كنسبة مئوية. |
| newHeight | Double | الارتفاع الجديد لمحتويات الصفحة كنسبة مئوية. |

### Return Value

true إذا كان تغيير الحجم ناجحًا.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)