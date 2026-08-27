---
title: "PdfFileEditor.TryAppend"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. يضيف الصفحات التي يتم اختيارها من مصفوفة Document في portStreams. يتضمن مستند النتيجة firstInputFile وجميع صفحات Document في portStreams في النطاق من startPage إلى endPage."
type: docs
weight: 380
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

يضيف الصفحات المختارة من مصفوفة المستندات في portStreams. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portStreams في النطاق من startPage إلى endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

## ملاحظات

طريقة TryAppend تشبه طريقة Append، إلا أن طريقة TryAppend لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

يضيف الصفحات المختارة من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles في النطاق من startPage إلى endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryAppend تشبه طريقة Append، إلا أن طريقة TryAppend لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


