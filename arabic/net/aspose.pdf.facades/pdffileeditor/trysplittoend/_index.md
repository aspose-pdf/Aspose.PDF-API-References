---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تقسم من الموقع وتخزن الجزء الخلفي كملف جديد
type: docs
weight: 470
url: /ar/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

تقسم من الموقع، وتخزن الجزء الخلفي كملف جديد.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المصدر. |
| location | Int32 | موضع التقسيم. |
| outputFile | String | مسار ملف Pdf الناتج. |

### Return Value

صحيح عند النجاح، أو خطأ.

## Remarks

طريقة TrySplitToEnd تشبه طريقة SplitToEnd، باستثناء أن طريقة TrySplitToEnd لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

تقسم من الموقع المحدد، وتخزن الجزء الخلفي كملف Stream جديد.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | ملف Pdf المصدر Stream. |
| location | Int32 | موضع التقسيم. |
| outputStream | Stream | ملف Pdf الناتج Stream. |

### Return Value

صحيح عند النجاح، أو خطأ.

## Remarks

التيارات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams. طريقة TrySplitToEnd تشبه طريقة SplitToEnd، باستثناء أن طريقة TrySplitToEnd لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

تقسم من الموقع المحدد، وتخزن الجزء الخلفي في كائن HttpResponse.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تيار الوثيقة المصدر. |
| location | Int32 | نقطة التقسيم. |
| response | HttpResponse | كائن HttpResponse. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TrySplitToEnd تشبه طريقة SplitToEnd، باستثناء أن طريقة TrySplitToEnd لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

تقسم من الموقع المحدد، وتخزن الجزء الخلفي في كائن HttpResponse.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | اسم الملف المصدر. |
| location | Int32 | نقطة التقسيم. |
| response | HttpResponse | كائنات HttpResponse. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TrySplitToEnd تشبه طريقة SplitToEnd، باستثناء أن طريقة TrySplitToEnd لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)