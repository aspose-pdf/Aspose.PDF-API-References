---
title: AddMarginsPct
second_title: Aspose.PDF لمرجع .NET API
description: تغيير حجم محتويات الصفحة وإضافة هوامش محددة . يتم تحديد الهوامش بالنسب المئوية من حجم الصفحة الأولي.
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

تغيير حجم محتويات الصفحة وإضافة هوامش محددة . يتم تحديد الهوامش بالنسب المئوية من حجم الصفحة الأولي.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | String | مسار الوثيقة المصدر. |
| destination | String | المسار حيث سيتم حفظ المستند الناتج. |
| pages | Int32[] | صفيف فهارس الصفحات. إذا كانت فارغة ، فستتم معالجة جميع صفحات المستند. |
| leftMargin | Double | الهامش الأيسر بالنسب المئوية لحجم الصفحة الأولي. |
| rightMargin | Double | الهامش الأيمن بالنسب المئوية لحجم الصفحة الأولي. |
| topMargin | Double | الهامش العلوي بالنسب المئوية لحجم الصفحة الأولي. |
| bottomMargin | Double | الهامش السفلي بالنسب المئوية لحجم الصفحة الأولي. |

### قيمة الإرجاع

صحيح إذا كان تغيير الحجم ناجحًا

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    // معالجة الصفحات 1 و 2 و 3
    new int[] { 1, 2, 3}, 
    // الهامش الأيسر هو 15٪ من عرض الصفحة 
    15, 
    // الهامش الأيمن هو 10٪ من عرض الصفحة
    10, 
    // الهامش العلوي 20٪ من عرض الصفحة
    20, 
    // الهامش السفلي 5٪ من عرض الصفحة
    5);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

تغيير حجم محتويات الصفحة وإضافة هوامش محددة . يتم تحديد الهوامش بالنسب المئوية من حجم الصفحة الأولي.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | Stream | الدفق الذي يحتوي على وثيقة المصدر. |
| destination | Stream | دفق حيث سيتم حفظ المستند الناتج. |
| pages | Int32[] | صفيف فهارس الصفحات. إذا كانت فارغة ، فستتم معالجة جميع صفحات المستند. |
| leftMargin | Double | الهامش الأيسر بالنسب المئوية لحجم الصفحة الأولي. |
| rightMargin | Double | الهامش الأيمن بالنسب المئوية لحجم الصفحة الأولي. |
| topMargin | Double | الهامش العلوي بالنسب المئوية لحجم الصفحة الأولي. |
| bottomMargin | Double | الهامش السفلي بالنسب المئوية لحجم الصفحة الأولي. |

### قيمة الإرجاع

صحيح إذا تم تنفيذ الإجراء بنجاح.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    // معالجة الصفحات 1 و 2 و 3
    new int[] { 1, 2, 3}, 
    // الهامش الأيسر هو 15٪ من عرض الصفحة 
    15, 
    // الهامش الأيمن هو 10٪ من عرض الصفحة
    10, 
    // الهامش العلوي 20٪ من عرض الصفحة
    20, 
    // الهامش السفلي 5٪ من عرض الصفحة
    5);
    dest.Close();
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->