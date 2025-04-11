---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تصنع مستند NUp من firstInputFile إلى outputFile
type: docs
weight: 440
url: /ar/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

تصنع مستند N-up وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة في ملف النتيجة. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

تصنع مستند N-up وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق المستند المصدر. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة في ملف النتيجة. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

تصنع مستند N-up وتخزن النتيجة في HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | اسم الملف المصدر. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

تصنع مستند N-up وتخزن النتيجة في HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق المستند المدخل. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| response | HttpResponse | HttpResponse حيث سيتم تخزين النتيجة. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

تصنع مستند N-Up من firstInputFile إلى outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf المدخل. |
| outputFile | String | مسار واسم ملف pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

تصنع مستند N-Up من تدفق المدخل وتخزن النتيجة في تدفق الناتج.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق pdf المدخل. |
| outputStream | Stream | تدفق pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

تصنع مستند N-Up من تدفق المدخل إلى تدفق الناتج.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق pdf المدخل. |
| outputStream | Stream | تدفق pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

تصنع مستند N-Up من ملفي PDF المدخلين إلى outputFile. كل صفحة من outputFile ستحتوي على صفحتين، صفحة واحدة من الملف المدخل الأول وأخرى من الملف المدخل الثاني. الصفحتان مكدستان أفقيًا.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | الملف المدخل الأول. |
| secondInputFile | String | الملف المدخل الثاني. |
| outputFile | String | مسار واسم ملف pdf الناتج. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

تصنع مستند N-Up من تدفقات PDF المدخلة إلى outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | التدفق المدخل الأول. |
| secondInputStream | Stream | التدفق المدخل الثاني. |
| outputStream | Stream | تدفق pdf الناتج. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

تصنع مستند N-Up من ملفات PDF المدخلة المتعددة إلى outputFile. كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في الملفات المدخلة بنفس رقم الصفحة. الصفحات المتعددة مكدسة أفقيًا إذا كانت isSidewise صحيحة ومكدسة عموديًا إذا كانت isSidewise خاطئة.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | ملفات Pdf المدخلة. |
| outputFile | String | مسار واسم ملف pdf الناتج. |
| isSidewise | Boolean | طريقة التكديس، صحيحة للأفقي وخاطئة للرأسي. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

تصنع مستند N-Up من تدفقات PDF المدخلة المتعددة إلى outputStream. كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في التدفقات المدخلة بنفس رقم الصفحة. الصفحات المتعددة مكدسة أفقيًا إذا كانت isSidewise صحيحة ومكدسة عموديًا إذا كانت isSidewise خاطئة.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | Stream[] | تدفقات Pdf المدخلة. |
| outputStream | Stream | تدفق pdf الناتج. |
| isSidewise | Boolean | طريقة التكديس، صحيحة للأفقي وخاطئة للرأسي. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

تصنع مستند N-Up من الملف المدخل إلى outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf المدخل. |
| outputFile | String | مسار واسم ملف pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |

### Return Value

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## Remarks

طريقة TryMakeNUp تشبه طريقة MakeNUp، باستثناء أن طريقة TryMakeNUp لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)