---
title: ResizeContents
second_title: Aspose.PDF لمرجع .NET API
description: يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة  تتم إضافة هوامش فارغة حول الصفحة.
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | String | مسار المستند المصدر. |
| destination | String | مسار وثيقة الوجهة. |
| pages | Int32[] | صفيف فهارس الصفحات (يبدأ فهرس الصفحة من 1). |
| parameters | ContentsResizeParameters | معلمات تغيير حجم الصفحة. |

### قيمة الإرجاع

صحيح إذا كان تغيير الحجم ناجحًا.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    // الهامش الأيسر = 10٪ من عرض الصفحة
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم حساب عرض المحتويات الجديدة تلقائيًا كعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    // الهامش الأيمن هو 10٪ من الصفحة 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم احتساب ارتفاع المحتويات الجديدة تلقائيًا (على غرار العرض)
    null,
    // الهامش السفلي 10٪
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### أنظر أيضا

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

يغير حجم صفحات المستند. تتم إضافة هوامش فارغة حول الصفحة المتقلصة.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | Document | مصدر وثائق. |
| pages | Int32[] | قائمة فهارس الصفحات. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    // الهامش الأيسر = 10٪ من عرض الصفحة
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم حساب عرض المحتويات الجديدة تلقائيًا كعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    // الهامش الأيمن هو 10٪ من الصفحة 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم احتساب ارتفاع المحتويات الجديدة تلقائيًا (على غرار العرض)
    null,
    // الهامش السفلي 10٪
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### أنظر أيضا

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

يغير حجم صفحات المستند. تتم إضافة هوامش فارغة حول الصفحة المتقلصة.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | Document | مصدر وثائق. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    // الهامش الأيسر = 10٪ من عرض الصفحة
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم حساب عرض المحتويات الجديدة تلقائيًا كعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    // الهامش الأيمن هو 10٪ من الصفحة 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم احتساب ارتفاع المحتويات الجديدة تلقائيًا (على غرار العرض)
    null,
    // الهامش السفلي 10٪
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### أنظر أيضا

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

تغيير حجم محتويات صفحات المستند.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | Stream | دفق مع المستند المصدر. |
| destination | Stream | دفق مع وثيقة الوجهة. |
| pages | Int32[] | صفيف فهارس الصفحات. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |

### قيمة الإرجاع

يعود صحيحا إذا نجح.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    // الهامش الأيسر = 10٪ من عرض الصفحة
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم حساب عرض المحتويات الجديدة تلقائيًا كعرض - الهامش الأيسر - الهامش الأيمن (100٪ - 10٪ - 10٪ = 80٪)
    null,
    // الهامش الأيمن هو 10٪ من الصفحة 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // الهامش العلوي = 10٪ من الارتفاع
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // يتم احتساب ارتفاع المحتويات الجديدة تلقائيًا (على غرار العرض)
    null,
    // الهامش السفلي 10٪
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### أنظر أيضا

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

يغير حجم محتويات صفحات الوثيقة. يتقلص محتويات الصفحة ويضيف هوامش . يتم تحديد الحجم الجديد للمحتويات في وحدات المساحة الافتراضية.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | Stream | الدفق الذي يحتوي على وثيقة المصدر. |
| destination | Stream | دفق حيث سيتم حفظ المستند الناتج. |
| pages | Int32[] | صفيف فهارس الصفحات. إذا كانت فارغة ، فستتم معالجة جميع صفحات المستند. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بوحدات المساحة الافتراضية. |
| newHeight | Double | ارتفاع جديد لمحتويات الصفحة بوحدات المساحة الافتراضية. |

### قيمة الإرجاع

صحيح إذا كان تغيير الحجم ناجحًا.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
// تغيير حجم كل صفحات المستند
null, 
// عرض المحتويات الجديدة = 200
200, 
// ارتفاع محتويات جديدة = 300
300);
// ستكون منطقة بقية الصفحة فارغة
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

يغير حجم محتويات صفحات الوثيقة. يتقلص محتويات الصفحة ويضيف هوامش . يتم تحديد الحجم الجديد للمحتويات في وحدات المساحة الافتراضية.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | String | مسار الوثيقة المصدر. |
| destination | String | المسار حيث سيتم حفظ المستند الناتج. |
| pages | Int32[] | صفيف فهارس الصفحات. إذا كانت فارغة ، فستتم معالجة جميع صفحات المستند. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بوحدات المساحة الافتراضية. |
| newHeight | Double | ارتفاع جديد لمحتويات الصفحة بوحدات المساحة الافتراضية. |

### قيمة الإرجاع

صحيح إذا كان تغيير الحجم ناجحًا.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
// تغيير حجم كل صفحات المستند
null, 
// عرض المحتويات الجديدة = 200
200, 
// ارتفاع محتويات جديدة = 300
300);
// ستكون منطقة بقية الصفحة فارغة
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse.

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | String | مسار الملف المصدر. |
| pages | Int32[] | صفيف من الصفحات المراد تغيير حجمها. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |
| response | HttpResponse | كائن HttpResponse حيث يتم حفظ النتيجة. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse.

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| source | Stream | دفق ملف المصدر. |
| pages | Int32[] | صفيف من الصفحات المراد تغيير حجمها. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |
| response | HttpResponse | كائن HttpResponse حيث يتم حفظ النتيجة. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
