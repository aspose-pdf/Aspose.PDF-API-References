---
title: ResizeContentsPct
second_title: Aspose.PDF لمرجع .NET API
description: تغيير حجم محتويات صفحات المستند. تقليص محتويات الصفحة وإضافة هوامش . يتم تحديد حجم محتويات جديد بالنسب المئوية.
type: docs
weight: 360
url: /ar/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

تغيير حجم محتويات صفحات المستند. تقليص محتويات الصفحة وإضافة هوامش . يتم تحديد حجم محتويات جديد بالنسب المئوية.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | String | مسار الوثيقة المصدر. |
| destination | String | المسار حيث سيتم حفظ المستند الناتج. |
| pages | Int32[] | صفيف فهارس الصفحات. إذا كانت فارغة ، فستتم معالجة جميع صفحات المستند. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بالنسب المئوية. |
| newHeight | Double | ارتفاع جديد لمحتويات الصفحة في percetns. |

### قيمة الإرجاع

صحيح إذا كان تغيير الحجم ناجحًا.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
// تغيير حجم كل صفحات المستند
null, 
// عرض المحتويات الجديدة = 60٪ من الحجم الأولي
60, 
// ارتفاع المحتويات الجديدة = 60٪ من الحجم الأولي
60);
// ستكون منطقة بقية الصفحة فارغة (هوامش الصفحة). حجم الهوامش اليمنى واليسرى (100٪ - 60٪) / 2 = 20٪
// نفس الشيء بالنسبة للهوامش العلوية والسفلية.
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

تغيير حجم محتويات صفحات المستند. تقليص محتويات الصفحة وإضافة هوامش . يتم تحديد حجم محتويات جديد بالنسب المئوية.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | Stream | الدفق الذي يحتوي على وثيقة المصدر. |
| destination | Stream | دفق حيث سيتم حفظ المستند الناتج. |
| pages | Int32[] | صفيف فهارس الصفحات. إذا كانت فارغة ، فستتم معالجة جميع صفحات المستند. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بالنسب المئوية. |
| newHeight | Double | ارتفاع جديد لمحتويات الصفحة في percetns. |

### قيمة الإرجاع

صحيح إذا تم تغيير حجمه بنجاح.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
// تغيير حجم كل صفحات المستند
null, 
// عرض المحتويات الجديدة = 60٪ من الحجم الأولي
60, 
// ارتفاع المحتويات الجديدة = 60٪ من الحجم الأولي
60);
// ستكون منطقة بقية الصفحة فارغة (هوامش الصفحة). حجم الهوامش اليمنى واليسرى (100٪ - 60٪) / 2 = 20٪
// نفس الشيء بالنسبة للهوامش العلوية والسفلية.
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->