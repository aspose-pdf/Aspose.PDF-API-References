---
title: "PdfFileEditor.MakeNUp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تنشئ مستند NUp من تدفقَي PDF المدخلين إلى outputStream"
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

ينشئ مستند N-Up من تدفقَي PDF الإدخال إلى outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputStream | Stream | دفق الإدخال الأول. |
| secondInputStream | Stream | دفق الإدخال الثاني. |
| outputStream | Stream | دفق pdf الناتج. |

### قيمة الإرجاع

منطقي - True للنجاح، أو false.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile. كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال ذات رقم الصفحة نفسه. تُرتب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFiles | String[] | ملفات Pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| isSidewise | Boolean | طريقة التجميع، true للأفقي و false للعمودي. |

### قيمة الإرجاع

منطقي - True للنجاح، أو false.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

ينشئ مستند N-Up من تدفقات PDF المتعددة إلى outputStream. كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال ذات رقم الصفحة نفسه. يتم ترتيب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStreams | Stream[] | دفقات Pdf الإدخال. |
| outputStream | Stream | دفق pdf الناتج. |
| isSidewise | Boolean | طريقة التجميع، true للأفقي و false للعمودي. |

### قيمة الإرجاع

منطقي - True للنجاح، أو false.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

ينشئ مستند N-Up من ملف الإدخال إلى outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |

### قيمة الإرجاع

منطقي - True للنجاح، أو false.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

ينشئ مستند N-Up من firstInputFile إلى outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### قيمة الإرجاع

منطقي - True للنجاح، أو false.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الإدخال. |
| outputStream | Stream | دفق pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### قيمة الإرجاع

منطقي - True للنجاح، أو false.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الإدخال. |
| outputStream | Stream | دفق pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

ينشئ مستند N-Up من ملفي PDF الإدخال إلى outputFile. كل صفحة من outputFile ستحتوي على صفحتين، إحداهما من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. تُرتب الصفحتان أفقياً.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الإدخالي الأول. |
| secondInputFile | String | ملف الإدخال الثاني. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |

### قيمة الإرجاع

منطقي - True للنجاح، أو false.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


