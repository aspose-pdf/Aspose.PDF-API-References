---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تعيد تحجيم محتويات صفحات الوثيقة
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

تعيد تحجيم محتويات صفحات الوثيقة.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | تدفق الوثيقة المصدر. |
| destination | Stream | تدفق الوثيقة الوجهة. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. |
| parameters | ContentsResizeParameters | معلمات التحجيم. |

### Return Value

ترجع true إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

تعيد تحجيم محتويات صفحات الوثيقة. تقلص محتويات الصفحة وتضيف هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | تدفق يحتوي على الوثيقة المصدر. |
| destination | Stream | تدفق حيث سيتم حفظ الوثيقة الناتجة. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |
| newHeight | Double | الارتفاع الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |

### Return Value

True إذا كانت عملية التحجيم ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

تعيد تحجيم محتويات صفحات الوثيقة. تقلص محتويات الصفحة وتضيف هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | مسار الوثيقة المصدر. |
| destination | String | المسار حيث سيتم حفظ الوثيقة الناتجة. |
| pages | Int32[] | مصفوفة من فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |
| newHeight | Double | الارتفاع الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |

### Return Value

true إذا كانت عملية التحجيم ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

تعيد تحجيم محتويات الصفحات في الوثيقة. إذا تم تقليص الصفحة، تتم إضافة هوامش فارغة حول الصفحة.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | مسار الوثيقة المصدر. |
| destination | String | مسار الوثيقة الوجهة. |
| pages | Int32[] | مصفوفة من فهارس الصفحات (يبدأ فهرس الصفحة من 1). |
| parameters | ContentsResizeParameters | معلمات تحجيم الصفحة. |

### Return Value

true إذا كانت عملية التحجيم ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

تعيد تحجيم صفحات الوثيقة. تتم إضافة هوامش فارغة حول الصفحة التي تم تقليصها.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Document | الوثيقة المصدر. |
| pages | Int32[] | قائمة بفهارس الصفحات. |
| parameters | ContentsResizeParameters | معلمات التحجيم. |

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

تعيد تحجيم صفحات الوثيقة. تتم إضافة هوامش فارغة حول الصفحة التي تم تقليصها.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Document | الوثيقة المصدر. |
| parameters | ContentsResizeParameters | معلمات التحجيم. |

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)