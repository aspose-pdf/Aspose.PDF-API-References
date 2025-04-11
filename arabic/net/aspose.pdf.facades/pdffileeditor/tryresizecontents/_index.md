---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تعيد حجم محتويات صفحات الوثيقة
type: docs
weight: 450
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

تعيد حجم محتويات الصفحات في الوثيقة. إذا تم تصغير الصفحة، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | مسار الملف المصدر. |
| pages | Int32[] | مصفوفة الصفحات التي سيتم تغيير حجمها. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |
| response | HttpResponse | كائن HttpResponse حيث يتم حفظ النتيجة. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryResizeContents تشبه طريقة ResizeContents، باستثناء أن طريقة TryResizeContents لا ترمي استثناءً إذا فشلت العملية.

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

تعيد حجم محتويات الصفحات في الوثيقة. إذا تم تصغير الصفحة، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | تدفق الملف المصدر. |
| pages | Int32[] | مصفوفة الصفحات التي سيتم تغيير حجمها. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |
| response | HttpResponse | كائن HttpResponse حيث يتم حفظ النتيجة. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryResizeContents تشبه طريقة ResizeContents، باستثناء أن طريقة TryResizeContents لا ترمي استثناءً إذا فشلت العملية.

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

تعيد حجم محتويات صفحات الوثيقة.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | تدفق الوثيقة المصدر. |
| destination | Stream | تدفق الوثيقة الوجهة. |
| pages | Int32[] | مصفوفة فهارس الصفحات. |
| parameters | ContentsResizeParameters | معلمات تغيير الحجم. |

### Return Value

ترجع true إذا كانت العملية ناجحة.

## Remarks

طريقة TryResizeContents تشبه طريقة ResizeContents، باستثناء أن طريقة TryResizeContents لا ترمي استثناءً إذا فشلت العملية.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

تعيد حجم محتويات صفحات الوثيقة. تصغر محتويات الصفحة وتضيف هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | تدفق يحتوي على الوثيقة المصدر. |
| destination | Stream | تدفق حيث سيتم حفظ الوثيقة الناتجة. |
| pages | Int32[] | مصفوفة فهارس الصفحات. إذا كانت null، فسيتم معالجة جميع صفحات الوثيقة. |
| newWidth | Double | العرض الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |
| newHeight | Double | الارتفاع الجديد لمحتويات الصفحة بوحدات الفضاء الافتراضية. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryResizeContents تشبه طريقة ResizeContents، باستثناء أن طريقة TryResizeContents لا ترمي استثناءً إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

تعيد حجم محتويات الصفحات في الوثيقة. إذا تم تصغير الصفحة، تتم إضافة هوامش فارغة حول الصفحة.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | مسار الوثيقة المصدر. |
| destination | String | مسار الوثيقة الوجهة. |
| pages | Int32[] | مصفوفة فهارس الصفحات (يبدأ فهرس الصفحة من 1). |
| parameters | ContentsResizeParameters | معلمات تغيير حجم الصفحة. |

### Return Value

true إذا كان تغيير الحجم ناجحًا.

## Remarks

طريقة TryResizeContents تشبه طريقة ResizeContents، باستثناء أن طريقة TryResizeContents لا ترمي استثناءً إذا فشلت العملية.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)