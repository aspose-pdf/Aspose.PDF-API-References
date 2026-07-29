---
title: "PdfFileEditor.ResizeContents"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تعيد تحجيم محتويات pages من document"
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

يعيد تحجيم محتويات صفحات المستند.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | Stream | دفق يحتوي على source document. |
| destination | Stream | دفق يحتوي على destination document. |
| صفحات | Int32[] | مصفوفة من فهارس page. |
| معلمات | ContentsResizeParameters | معلمات التحجيم. |

### قيمة الإرجاع

يرجع true إذا نجح.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //الهامش الأيسر = 10٪ من عرض page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //عرض المحتويات الجديد يُحسب تلقائيًا كالعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    //الهامش الأيمن هو 10٪ من page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ارتفاع المحتوى الجديد يتم حسابه تلقائيًا (مشابه للعرض)
    null,
    //الهامش السفلي هو 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### انظر أيضًا

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | Stream | تدفق يحتوي على المستند المصدر. |
| destination | Stream | دفق حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |
| newHeight | Double | الارتفاع الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |

### قيمة الإرجاع

True إذا كان التحجيم ناجحًا.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//إعادة تحجيم جميع صفحات المستند
null, 
//عرض المحتوى الجديد = 200
200, 
//ارتفاع المحتوى الجديد = 300
300);
// ستكون مساحة الصفحة المتبقية فارغة
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | String | المسار إلى source document. |
| destination | String | المسار حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |
| newHeight | Double | الارتفاع الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |

### قيمة الإرجاع

صحيح إذا نجح تغيير الحجم.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//إعادة تحجيم جميع صفحات المستند
null, 
//عرض المحتوى الجديد = 200
200, 
//ارتفاع المحتوى الجديد = 300
300);
// ستكون مساحة الصفحة المتبقية فارغة
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

يعيد تحجيم محتويات الصفحات في المستند. إذا تم تقليص الصفحة تُضاف هوامش فارغة حولها.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | String | مسار المستند المصدر. |
| destination | String | مسار المستند الوجهة. |
| صفحات | Int32[] | مصفوفة مؤشرات الصفحات (يبدأ مؤشر الصفحة من 1). |
| معلمات | ContentsResizeParameters | معلمات إعادة تحجيم الصفحة. |

### قيمة الإرجاع

صحيح إذا نجح تغيير الحجم.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //الهامش الأيسر = 10٪ من عرض page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //عرض المحتويات الجديد يُحسب تلقائيًا كالعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    //الهامش الأيمن هو 10٪ من page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ارتفاع المحتوى الجديد يتم حسابه تلقائيًا (مشابه للعرض)
    null,
    //الهامش السفلي هو 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### انظر أيضًا

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

يعيد تحجيم صفحات المستند. تُضاف هوامش فارغة حول الصفحة المصغرة.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | Document | المستند المصدر. |
| صفحات | Int32[] | قائمة مؤشرات الصفحات. |
| معلمات | ContentsResizeParameters | معلمات التحجيم. |

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //الهامش الأيسر = 10٪ من عرض page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //عرض المحتويات الجديد يُحسب تلقائيًا كالعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    //الهامش الأيمن هو 10٪ من page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ارتفاع المحتوى الجديد يتم حسابه تلقائيًا (مشابه للعرض)
    null,
    //الهامش السفلي هو 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

يعيد تحجيم صفحات المستند. تُضاف هوامش فارغة حول الصفحة المصغرة.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | Document | المستند المصدر. |
| معلمات | ContentsResizeParameters | معلمات التحجيم. |

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //الهامش الأيسر = 10٪ من عرض page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //عرض المحتويات الجديد يُحسب تلقائيًا كالعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    //الهامش الأيمن هو 10٪ من page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ارتفاع المحتوى الجديد يتم حسابه تلقائيًا (مشابه للعرض)
    null,
    //الهامش السفلي هو 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


