---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. يدمج ملفين
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

يدمج ملفين.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | الملف الأول للدمج. |
| secInputFile | String | الملف الثاني للدمج. |
| outputFile | String | ملف الإخراج. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

يدمج ملفين.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | تدفق الملف الأول. |
| secInputStream | Stream | تدفق الملف الثاني. |
| outputStream | Stream | التدفق الذي سيتم تخزين ملف النتيجة فيه. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

يدمج المستندات.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| src | Document[] | مصفوفة من المستندات المصدر. |
| dest | Document | المستند الوجهة. |

### Return Value

صحيح إذا كان الدمج ناجحًا.

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

يدمج الملفات في ملف واحد.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | مصفوفة من الملفات للدمج. |
| outputFile | String | اسم ملف الإخراج. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

يدمج الملفات

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة من التدفقات التي سيتم دمجها. |
| outputStream | Stream | التدفق الذي سيتم تخزين ملف النتيجة فيه. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

يمزج بين مستندين Pdf في مستند Pdf جديد مع صفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج المستندين Pdf إلى إنتاج المستند الناتج مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | الملف الأول. |
| secInputFile | String | الملف الثاني. |
| blankPageFile | String | ملف PDF مع صفحة فارغة. |
| outputFile | String | ملف النتيجة. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

يمزج بين مستندين Pdf في مستند Pdf جديد مع صفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج المستندين Pdf إلى إنتاج المستند الناتج مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | التدفق الأول لـ Pdf. |
| secInputStream | Stream | التدفق الثاني لـ Pdf. |
| blankPageStream | Stream | التدفق لـ Pdf مع صفحة فارغة. |
| outputStream | Stream | تدفق Pdf الناتج. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## Concatenate(string[], HttpResponse) {#concatenate_8}

يدمج الملفات ويحفظ النتيجة في كائن HttpResponse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | مصفوفة من الملفات للدمج. |
| response | HttpResponse | كائن الاستجابة. |

### Return Value

صحيح إذا كان الدمج ناجحًا.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

يدمج الملفات ويخزن النتيجة في كائن HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | مصفوفة التدفقات التي تحتوي على الملفات للدمج. |
| response | HttpResponse | كائن الاستجابة. |

### Return Value

صحيح إذا كانت العملية ناجحة.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)