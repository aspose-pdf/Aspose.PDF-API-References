---
title: "PdfFileEditor.Append"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. يضيف الصفحات التي يتم اختيارها من مصفوفة Document في portStreams. يتضمن مستند النتيجة firstInputFile وجميع صفحات Document في portStreams في النطاق من startPage إلى endPage."
type: docs
weight: 250
url: /ar/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

يضيف الصفحات المختارة من مصفوفة المستندات في portStreams. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portStreams في النطاق من startPage إلى endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق Pdf الإدخال. |
| portStreams | Stream[] | Document لنسخ الصفحات منها. |
| startPage | Int32 | يبدأ Page في Document في portStreams. |
| endPage | Int32 | ينتهي Page في Document في portStreams. |
| outputStream | Stream | دفق Pdf الإخراج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

يضيف الصفحات المختارة من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles في النطاق من startPage إلى endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف Pdf الإدخال. |
| portFiles | String[] | Document لنسخ الصفحات منها. |
| startPage | Int32 | يبدأ Page في Document في portFiles. |
| endPage | Int32 | ينتهي Page في Document في portFiles. |
| outputFile | String | مستند Pdf الإخراج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

يضيف الصفحات المختارة من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف Pdf الإدخال. |
| portFile | String | صفحات من ملف Pdf. |
| startPage | Int32 | يبدأ Page في portFile. |
| endPage | Int32 | ينتهي Page في portFile. |
| outputFile | String | مستند Pdf الإخراج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

يضيف الصفحات المختارة من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق ملف الإدخال. |
| portStream | Stream | صفحات من تدفق ملف Pdf. |
| startPage | Int32 | تبدأ الصفحة في تدفق portFile. |
| endPage | Int32 | تنتهي الصفحة في تدفق portFile. |
| outputStream | Stream | تدفق ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


