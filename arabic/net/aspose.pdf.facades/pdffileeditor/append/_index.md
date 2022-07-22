---
title: Append
second_title: Aspose.PDF لمرجع .NET API
description: لإلحاق الصفحات  التي يتم اختيارها من مجموعة من المستندات في portStreams. يتضمن مستند النتيجة firstInputFile وجميع صفحات مستندات portStreams في النطاق من صفحة البداية إلى الصفحة النهائية.
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

لإلحاق الصفحات ، التي يتم اختيارها من مجموعة من المستندات في portStreams. يتضمن مستند النتيجة firstInputFile وجميع صفحات مستندات portStreams في النطاق من صفحة البداية إلى الصفحة النهائية.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | إدخال دفق PDF. |
| portStreams | Stream[] | مستندات لنسخ صفحات منها. |
| startPage | Int32 | تبدأ الصفحة في مستندات portStreams. |
| endPage | Int32 | تنتهي الصفحة في مستندات portStreams. |
| outputStream | Stream | إخراج دفق PDF. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

لإلحاق الصفحات التي يتم اختيارها من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles الموجودة في نطاق بدء الصفحة حتى نهاية الصفحة.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال ملف PDF. |
| portFiles | String[] | مستندات لنسخ صفحات منها. |
| startPage | Int32 | تبدأ الصفحة في مستندات portFiles. |
| endPage | Int32 | تنتهي الصفحة في مستندات portFiles. |
| outputFile | String | إخراج وثيقة PDF. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

لإلحاق الصفحات ، التي يتم اختيارها من ملف المنفذ داخل النطاق من صفحة البداية إلى الصفحة النهائية ، في portFile في نهاية firstInputFile .

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال ملف PDF. |
| portFile | String | صفحات من ملف PDF. |
| startPage | Int32 | تبدأ الصفحة في portFile. |
| endPage | Int32 | تنتهي الصفحة في portFile. |
| outputFile | String | إخراج وثيقة PDF. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

لإلحاق الصفحات ، التي يتم اختيارها من portStream ضمن النطاق من صفحة البداية إلى الصفحة النهائية ، في portStream في نهاية firstInputStream .

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق ملف الإدخال. |
| portStream | Stream | صفحات من ملف Pdf Stream. |
| startPage | Int32 | تبدأ الصفحة في دفق ملف المنفذ. |
| endPage | Int32 | تنتهي الصفحة في دفق ملف المنفذ. |
| outputStream | Stream | إخراج ملف Pdf دفق. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

إلحاق مستندات بالمستند المصدر وحفظ النتيجة في كائن الاستجابة.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | الدفق الذي يحتوي على وثيقة المصدر. |
| portStreams | Stream[] | صفيف من التدفقات مع المستندات المطلوب إلحاقها. |
| startPage | Int32 | صفحة البداية للصفحة الملحقة. |
| endPage | Int32 | صفحة نهاية الصفحات الملحقة. |
| response | HttpResponse | كائن الاستجابة حيث سيتم حفظ المستند. |

### قيمة الإرجاع

صحيح إذا كانت العملية ناجحة.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

إلحاق مستندات بالمستند المصدر وحفظ النتيجة في كائن HttpResponse .

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | اسم الملف الذي يحتوي على وثيقة المصدر. |
| portFiles | String[] | مصفوفة أسماء الملفات التي تحتوي على مستندات ملحقة. |
| startPage | Int32 | صفحة البداية للصفحات الملحقة. |
| endPage | Int32 | صفحة نهاية الصفحات الملحقة. |
| response | HttpResponse | كائن الاستجابة حيث سيتم حفظ المستند. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
