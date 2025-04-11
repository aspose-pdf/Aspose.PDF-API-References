---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. يدمج ملفين
type: docs
weight: 390
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

يدمج ملفين.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول للدمج. |
| secInputFile | String | الملف الثاني للدمج. |
| outputFile | String | ملف الإخراج. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

يدمج المستندات.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | Document[] | مصفوفة من المستندات المصدر. |
| dest | Document | المستند الوجهة. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

يدمج الملفات في ملف واحد.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFiles | String[] | مصفوفة من الملفات للدمج. |
| outputFile | String | اسم ملف الإخراج. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

يدمج الملفات

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة من التدفقات التي سيتم دمجها. |
| outputStream | Stream | التدفق الذي سيتم تخزين ملف النتيجة فيه. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

يمزج بين مستندين Pdf في مستند Pdf جديد مع صفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي document1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي document2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج مستندي Pdf إلى إنتاج مستند النتيجة مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول. |
| secInputFile | String | الملف الثاني. |
| blankPageFile | String | ملف PDF مع صفحة فارغة. |
| outputFile | String | ملف النتيجة. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

يمزج بين مستندين Pdf في مستند Pdf جديد مع صفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي document1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي document2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج مستندي Pdf إلى إنتاج مستند النتيجة مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstInputStream | Stream | أول تدفق Pdf. |
| secInputStream | Stream | ثاني تدفق Pdf. |
| blankPageStream | Stream | تدفق Pdf مع صفحة فارغة. |
| outputStream | Stream | تدفق Pdf للإخراج. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

يدمج الملفات ويحفظ النتيجة في كائن HttpResponse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFiles | String[] | مصفوفة من الملفات للدمج. |
| response | HttpResponse | كائن الاستجابة. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

يدمج الملفات ويخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة التدفقات التي تحتوي على الملفات للدمج. |
| response | HttpResponse | كائن الاستجابة. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، باستثناء أن طريقة TryConcatenate لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)