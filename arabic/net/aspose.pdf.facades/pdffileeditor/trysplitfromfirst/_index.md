---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد وت saves الجزء الأمامي كملف جديد
type: docs
weight: 460
url: /ar/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

تقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد، وت saves الجزء الأمامي كملف جديد.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المصدر. |
| location | Int32 | نقطة التقسيم. |
| outputFile | String | ملف Pdf الناتج. |

### Return Value

True للنجاح، أو false.

## Remarks

طريقة TrySplitFromFirst تشبه طريقة SplitFromFirst، باستثناء أن طريقة TrySplitFromFirst لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

تقسم من البداية إلى الموقع المحدد، وت saves الجزء الأمامي في Stream الناتج.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream ملف Pdf المصدر. |
| location | Int32 | نقطة التقسيم. |
| outputStream | Stream | Stream الملف الناتج. |

### Return Value

True للنجاح، أو false.

## Remarks

الـ Streams لا تُغلق بعد هذه العملية. طريقة TrySplitFromFirst تشبه طريقة SplitFromFirst، باستثناء أن طريقة TrySplitFromFirst لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

تقسم المستند من الصفحة الأولى إلى الموقع وت saves النتيجة في كائنات HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | اسم الملف المصدر. |
| location | Int32 | نقطة التقسيم. |
| response | HttpResponse | كائنات HttpResponse. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TrySplitFromFirst تشبه طريقة SplitFromFirst، باستثناء أن طريقة TrySplitFromFirst لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

تقسم المستند من البداية إلى الموقع المحدد وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream المستند المصدر. |
| location | Int32 | نقطة التقسيم. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TrySplitFromFirst تشبه طريقة SplitFromFirst، باستثناء أن طريقة TrySplitFromFirst لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)