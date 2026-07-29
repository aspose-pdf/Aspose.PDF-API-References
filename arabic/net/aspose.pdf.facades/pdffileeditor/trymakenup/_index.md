---
title: "PdfFileEditor.TryMakeNUp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تنشئ مستند NUp من firstInputFile إلى outputFile"
type: docs
weight: 440
url: /ar/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

ينشئ مستند N-Up من firstInputFile إلى outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### قيمة الإرجاع

true إذا تم إكمال العملية بنجاح؛ وإلا، false.

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الإدخال. |
| outputStream | Stream | دفق pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الإدخال. |
| outputStream | Stream | دفق pdf الناتج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

ينشئ مستند N-Up من ملفي PDF الإدخال إلى outputFile. كل صفحة من outputFile ستحتوي على صفحتين، إحداهما من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. تُرتب الصفحتان أفقياً.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الإدخالي الأول. |
| secondInputFile | String | ملف الإدخال الثاني. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |

### قيمة الإرجاع

true إذا تم إكمال العملية بنجاح؛ وإلا، false

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

ينشئ مستند N-Up من تدفقَي PDF الإدخال إلى outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputStream | Stream | دفق الإدخال الأول. |
| secondInputStream | Stream | دفق الإدخال الثاني. |
| outputStream | Stream | دفق pdf الناتج. |

### قيمة الإرجاع

true إذا تم إكمال العملية بنجاح؛ وإلا، false

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile. كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال ذات رقم الصفحة نفسه. تُرتب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFiles | String[] | ملفات Pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| isSidewise | Boolean | طريقة التجميع، true للأفقي و false للعمودي. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

ينشئ مستند N-Up من تدفقات PDF المتعددة إلى outputStream. كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال ذات رقم الصفحة نفسه. يتم ترتيب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStreams | Stream[] | دفقات Pdf الإدخال. |
| outputStream | Stream | دفق pdf الناتج. |
| isSidewise | Boolean | طريقة التجميع، true للأفقي و false للعمودي. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

ينشئ مستند N-Up من ملف الإدخال إلى outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeNUp تشبه طريقة MakeNUp، إلا أن طريقة TryMakeNUp لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


