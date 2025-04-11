---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تصنع مستند NUp من تدفقات PDF المدخلة إلى outputStream
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

تصنع مستند N-Up من firstInputFile إلى outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف PDF المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

تصنع مستند N-Up من تدفق المدخلات وتخزن النتيجة في تدفق الإخراج.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

تصنع مستند N-Up من تدفق المدخلات الأول إلى تدفق الإخراج.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف PDF الناتج. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

تصنع مستند N-Up من ملفي PDF المدخلين إلى outputFile. ستحتوي كل صفحة من outputFile على صفحتين، واحدة من ملف الإدخال الأول وأخرى من ملف الإدخال الثاني. الصفحتان مكدستان أفقيًا.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | ملف الإدخال الأول. |
| secondInputFile | String | ملف الإدخال الثاني. |
| outputFile | String | مسار واسم ملف PDF الناتج. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

تصنع مستند N-Up من تدفقات PDF المدخلة إلى outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | تدفق الإدخال الأول. |
| secondInputStream | Stream | تدفق الإدخال الثاني. |
| outputStream | Stream | تدفق PDF الناتج. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

تصنع مستند N-Up من ملفات PDF المدخلة المتعددة إلى outputFile. ستحتوي كل صفحة من outputFile على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال بنفس رقم الصفحة. الصفحات المتعددة مكدسة أفقيًا إذا كانت isSidewise صحيحة ومكدسة عموديًا إذا كانت isSidewise خاطئة.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | ملفات PDF المدخلة. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| isSidewise | Boolean | طريقة التكديس، صحيح للأفقي وخاطئ للرأسي. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

تصنع مستند N-Up من تدفقات PDF المدخلة المتعددة إلى outputStream. ستحتوي كل صفحة من outputStream على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال بنفس رقم الصفحة. الصفحات المتعددة مكدسة أفقيًا إذا كانت isSidewise صحيحة ومكدسة عموديًا إذا كانت isSidewise خاطئة.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | Stream[] | تدفقات PDF المدخلة. |
| outputStream | Stream | تدفق PDF الناتج. |
| isSidewise | Boolean | طريقة التكديس، صحيح للأفقي وخاطئ للرأسي. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

تصنع مستند N-Up من ملف الإدخال إلى outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف PDF المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف PDF الناتج. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

تصنع مستند N-Up من firstInputFile إلى outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف PDF المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

تصنع مستند N-Up من تدفق المدخلات وتخزن النتيجة في تدفق الإخراج.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

تصنع مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف PDF الناتج. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

تصنع مستند N-Up من ملفي PDF المدخلين إلى outputFile. ستحتوي كل صفحة من outputFile على صفحتين، واحدة من ملف الإدخال الأول وأخرى من ملف الإدخال الثاني. الصفحتان مكدستان أفقيًا.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | ملف الإدخال الأول. |
| secondInputFile | String | ملف الإدخال الثاني. |
| outputFile | String | مسار واسم ملف PDF الناتج. |

### Return Value

boolean - صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)