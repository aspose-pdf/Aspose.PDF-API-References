---
title: "PdfFileEditor.Concatenate"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تقوم بدمج ملفين"
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

يقوم بدمج ملفين.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول للدمج. |
| secInputFile | String | الملف الثاني للدمج. |
| outputFile | String | ملف الإخراج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

يقوم بدمج ملفين.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputStream | Stream | دفق الملف الأول. |
| secInputStream | Stream | دفق الملف الثاني. |
| outputStream | Stream | دفق حيث سيتم تخزين ملف النتيجة. |

### قيمة الإرجاع

True إذا نجحت العملية.

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

يدمج المستندات.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| src | Document[] | مصفوفة المستندات المصدر. |
| dest | Document | المستند الوجهة. |

### قيمة الإرجاع

True إذا كان الدمج ناجحًا.

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

يقوم بدمج الملفات في ملف واحد.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFiles | String[] | مصفوفة الملفات للدمج. |
| outputFile | String | اسم ملف الإخراج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

يدمج الملفات.

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة من التدفقات التي سيتم دمجها. |
| outputStream | Stream | دفق حيث سيتم تخزين ملف النتيجة. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول. |
| secInputFile | String | الملف الثاني. |
| blankPageFile | String | ملف PDF يحتوي على صفحة فارغة. |
| outputFile | String | ملف النتيجة. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| firstInputStream | Stream | تدفق Pdf الأول. |
| secInputStream | Stream | تدفق Pdf الثاني. |
| blankPageStream | Stream | تدفق Pdf مع صفحة فارغة. |
| outputStream | Stream | تدفق Pdf الناتج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


