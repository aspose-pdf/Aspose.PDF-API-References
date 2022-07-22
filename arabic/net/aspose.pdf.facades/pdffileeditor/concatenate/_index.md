---
title: Concatenate
second_title: Aspose.PDF لمرجع .NET API
description: يربط بين ملفين.
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_5}

يربط بين ملفين.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول لسلسلة. |
| secInputFile | String | الملف الثاني لسلسلة. |
| outputFile | String | ملف إلاخراج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

يربط بين ملفين.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstInputStream | Stream | دفق الملف الأول. |
| secInputStream | Stream | دفق الملف الثاني. |
| outputStream | Stream | دفق حيث سيتم تخزين ملف النتيجة. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

تسلسل المستندات .

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| src | Document[] | صفيف من المستندات المصدر. |
| dest | Document | وثيقة الوجهة. |

### قيمة الإرجاع

صحيح إذا كان التسلسل ناجحًا.

### أنظر أيضا

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_7}

يربط الملفات في ملف واحد.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFiles | String[] | صفيف من الملفات المراد تجميعها. |
| outputFile | String | اسم ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

تسلسل الملفات

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة من التدفقات المراد تسلسلها. |
| outputStream | Stream | دفق حيث سيتم تخزين ملف النتيجة. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_6}

يدمج مستندين من ملفات PDF في مستند Pdf جديد مع الصفحات بطرق بديلة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند 1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند 2 على 3 صفحات: p1 '، p2'، p3 '. دمج ملفي PDF سينتج المستند الناتج بالصفحات: p1، p1'، p2، p2 '، p3، p3'، p4، blankpage، p5، blankpage .

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstInputFile | String | الملف الأول. |
| secInputFile | String | الملف الثاني. |
| blankPageFile | String | ملف PDF بصفحة فارغة. |
| outputFile | String | الملف الناتج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

يدمج مستندين من ملفات PDF في مستند Pdf جديد مع الصفحات بطرق بديلة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند 1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند 2 على 3 صفحات: p1 '، p2'، p3 '. دمج ملفي PDF سينتج المستند الناتج بالصفحات: p1، p1'، p2، p2 '، p3، p3'، p4، blankpage، p5، blankpage .

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstInputStream | Stream | أول دفق PDF. |
| secInputStream | Stream | دفق PDF الثاني. |
| blankPageStream | Stream | دفق PDF بصفحة فارغة. |
| outputStream | Stream | إخراج دفق PDF. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(string[], HttpResponse) {#concatenate_8}

يربط الملفات ويحفظ reslt في كائن HttpResposnse .

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFiles | String[] | صفيف من الملفات المراد تجميعها. |
| response | HttpResponse | كائن الاستجابة. |

### قيمة الإرجاع

صحيح إذا كان التسلسل ناجحًا.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

تؤدي الملفات المتسلسلة والمخازن إلى كائن HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة التدفقات التي تحتوي على ملفات للتسلسل. |
| response | HttpResponse | كائن الاستجابة / |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
