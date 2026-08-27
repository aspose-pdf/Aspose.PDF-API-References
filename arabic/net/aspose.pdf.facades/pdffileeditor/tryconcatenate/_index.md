---
title: "PdfFileEditor.TryConcatenate"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تقوم بدمج ملفين"
type: docs
weight: 390
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

يقوم بدمج ملفين.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول للدمج. |
| secInputFile | String | الملف الثاني للدمج. |
| outputFile | String | ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، إلا أن طريقة TryConcatenate لا تُطلق استثناءً إذا فشلت العملية.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| src | Document[] | مصفوفة المستندات المصدر. |
| dest | Document | المستند الوجهة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، إلا أن طريقة TryConcatenate لا تُطلق استثناءً إذا فشلت العملية.

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

يقوم بدمج الملفات في ملف واحد.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFiles | String[] | مصفوفة الملفات للدمج. |
| outputFile | String | اسم ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، إلا أن طريقة TryConcatenate لا تُطلق استثناءً إذا فشلت العملية.

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

يدمج الملفات.

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة من التدفقات التي سيتم دمجها. |
| outputStream | Stream | دفق حيث سيتم تخزين ملف النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، إلا أن طريقة TryConcatenate لا تُطلق استثناءً إذا فشلت العملية.

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

يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول. |
| secInputFile | String | الملف الثاني. |
| blankPageFile | String | ملف PDF يحتوي على صفحة فارغة. |
| outputFile | String | ملف النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، إلا أن طريقة TryConcatenate لا تُطلق استثناءً إذا فشلت العملية.

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

يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputStream | Stream | تدفق Pdf الأول. |
| secInputStream | Stream | تدفق Pdf الثاني. |
| blankPageStream | Stream | تدفق Pdf مع صفحة فارغة. |
| outputStream | Stream | تدفق Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryConcatenate تشبه طريقة Concatenate، إلا أن طريقة TryConcatenate لا تُطلق استثناءً إذا فشلت العملية.

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


