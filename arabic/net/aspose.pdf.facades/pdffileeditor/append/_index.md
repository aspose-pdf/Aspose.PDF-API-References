---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. يضيف صفحات تم اختيارها من مصفوفة الوثائق في portStreams. الوثيقة الناتجة تشمل firstInputFile وجميع صفحات وثائق portStreams في النطاق من startPage إلى endPage
type: docs
weight: 250
url: /ar/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

يضيف صفحات، تم اختيارها من مصفوفة الوثائق في portStreams. الوثيقة الناتجة تشمل firstInputFile وجميع صفحات وثائق portStreams في النطاق من startPage إلى endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق Pdf المدخل. |
| portStreams | Stream[] | الوثائق لنسخ الصفحات منها. |
| startPage | Int32 | الصفحة تبدأ في وثائق portStreams. |
| endPage | Int32 | الصفحة تنتهي في وثائق portStreams. |
| outputStream | Stream | تدفق Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

يضيف صفحات، تم اختيارها من وثائق portFiles. الوثيقة الناتجة تشمل firstInputFile وجميع صفحات وثائق portFiles في النطاق من startPage إلى endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المدخل. |
| portFiles | String[] | الوثائق لنسخ الصفحات منها. |
| startPage | Int32 | الصفحة تبدأ في وثائق portFiles. |
| endPage | Int32 | الصفحة تنتهي في وثائق portFiles. |
| outputFile | String | وثيقة Pdf الناتجة. |

### Return Value

صحيح إذا كانت العملية قد نجحت.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

يضيف صفحات، تم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المدخل. |
| portFile | String | صفحات من ملف Pdf. |
| startPage | Int32 | الصفحة تبدأ في portFile. |
| endPage | Int32 | الصفحة تنتهي في portFile. |
| outputFile | String | وثيقة Pdf الناتجة. |

### Return Value

صحيح إذا كانت العملية قد نجحت.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

يضيف صفحات، تم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق الملف المدخل. |
| portStream | Stream | صفحات من تدفق ملف Pdf. |
| startPage | Int32 | الصفحة تبدأ في تدفق portFile. |
| endPage | Int32 | الصفحة تنتهي في تدفق portFile. |
| outputStream | Stream | تدفق ملف Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)