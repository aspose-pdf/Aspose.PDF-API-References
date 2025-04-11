---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال وتحفظ كملف Pdf جديد
type: docs
weight: 400
url: /ar/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

تحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، وتحفظ كملف Pdf جديد.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة من ملف الإدخال. |
| outputFile | String | مسار ملف الإخراج. |

### Return Value

true إذا اكتملت العملية بنجاح؛ وإلا، false.

## Remarks

طريقة TryDelete تشبه طريقة Delete، باستثناء أن طريقة TryDelete لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

تحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، وتحفظ كملف Pdf جديد.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة من ملف الإدخال. |
| outputStream | Stream | تدفق ملف الإخراج. |

### Return Value

True للنجاح، أو false.

## Remarks

طريقة TryDelete تشبه طريقة Delete، باستثناء أن طريقة TryDelete لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

تحذف الصفحات المحددة من المستند وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار ملف المصدر. |
| pageNumber | Int32[] | مصفوفة أرقام الصفحات التي يجب حذفها. |
| response | HttpResponse | كائن الاستجابة حيث سيتم تخزين المستند الناتج. |

### Return Value

true إذا اكتملت العملية بنجاح؛ وإلا، false.

## Remarks

طريقة TryDelete تشبه طريقة Delete، باستثناء أن طريقة TryDelete لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

تحذف الصفحات المحددة من المستند وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق المستند المصدر. |
| pageNumber | Int32[] | مصفوفة أرقام الصفحات التي سيتم حذفها. |
| response | HttpResponse | كائن HttpResponse |

### Return Value

true إذا اكتملت العملية بنجاح؛ وإلا، false.

## Remarks

طريقة TryDelete تشبه طريقة Delete، باستثناء أن طريقة TryDelete لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)