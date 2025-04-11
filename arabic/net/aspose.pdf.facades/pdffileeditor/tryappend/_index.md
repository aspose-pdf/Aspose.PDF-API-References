---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. يضيف صفحات تم اختيارها من مصفوفة الوثائق في portStreams. الوثيقة الناتجة تشمل firstInputFile وجميع صفحات وثائق portStreams في النطاق من startPage إلى endPage
type: docs
weight: 380
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

يضيف صفحات، التي تم اختيارها من مصفوفة الوثائق في portStreams. الوثيقة الناتجة تشمل firstInputFile وجميع صفحات وثائق portStreams في النطاق من startPage إلى endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق Pdf المدخل. |
| portStreams | Stream[] | الوثائق لنسخ الصفحات منها. |
| startPage | Int32 | الصفحة تبدأ في وثائق portStreams. |
| endPage | Int32 | الصفحة تنتهي في وثائق portStreams. |
| outputStream | Stream | تدفق Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Remarks

طريقة TryAppend تشبه طريقة Append، باستثناء أن طريقة TryAppend لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

يضيف صفحات، التي تم اختيارها من وثائق portFiles. الوثيقة الناتجة تشمل firstInputFile وجميع صفحات وثائق portFiles في النطاق من startPage إلى endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المدخل. |
| portFiles | String[] | الوثائق لنسخ الصفحات منها. |
| startPage | Int32 | الصفحة تبدأ في وثائق portFiles. |
| endPage | Int32 | الصفحة تنتهي في وثائق portFiles. |
| outputFile | String | وثيقة Pdf الناتجة. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TryAppend تشبه طريقة Append، باستثناء أن طريقة TryAppend لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

يضيف الوثائق إلى الوثيقة المصدر ويحفظ النتيجة في كائن الاستجابة.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق يحتوي على الوثيقة المصدر. |
| portStreams | Stream[] | مصفوفة من التدفقات مع الوثائق التي سيتم إضافتها. |
| startPage | Int32 | الصفحة الأولى من الصفحات المضافة. |
| endPage | Int32 | الصفحة الأخيرة من الصفحات المضافة. |
| response | HttpResponse | كائن الاستجابة حيث سيتم حفظ الوثيقة. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TryAppend تشبه طريقة Append، باستثناء أن طريقة TryAppend لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

يضيف الوثائق إلى الوثيقة المصدر ويحفظ النتيجة في كائن HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | اسم الملف الذي يحتوي على الوثيقة المصدر. |
| portFiles | String[] | مصفوفة من أسماء الملفات التي تحتوي على الوثائق المضافة. |
| startPage | Int32 | الصفحة الأولى من الصفحات المضافة. |
| endPage | Int32 | الصفحة الأخيرة من الصفحات المضافة. |
| response | HttpResponse | كائن الاستجابة حيث سيتم حفظ الوثيقة. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TryAppend تشبه طريقة Append، باستثناء أن طريقة TryAppend لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)