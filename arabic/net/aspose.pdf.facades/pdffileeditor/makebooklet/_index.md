---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تصنع كتيب من ملف الإدخال إلى ملف الإخراج
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

تصنع كتيب من ملف الإدخال إلى ملف الإخراج.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف PDF المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |

### قيمة الإرجاع

boolean - صحيح للنجاح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

تصنع كتيب من InputStream إلى outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |

### قيمة الإرجاع

صحيح إذا كانت العملية قد نجحت.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

تصنع كتيب من inputFile إلى outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف PDF المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| pageSize | PageSize | حجم صفحة ملف PDF الناتج. |

### قيمة الإرجاع

صحيح إذا كانت العملية قد نجحت.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

تصنع كتيب من تدفق الإدخال وتحفظ النتيجة في تدفق الإخراج.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| pageSize | PageSize | حجم صفحة ملف PDF الناتج. |

### قيمة الإرجاع

صحيح إذا كانت العملية قد نجحت.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

تصنع كتيب مخصص من firstInputFile إلى outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | الملف المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى من الكتيب. |
| rightPages | Int32[] | الصفحات اليمنى من الكتيب. |

### قيمة الإرجاع

boolean - صحيح للنجاح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

تصنع كتيب مخصص من firstInputStream إلى outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | التدفق المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

boolean - صحيح للنجاح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

تصنع كتيب مخصص من firstInputFile إلى outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | الملف المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| pageSize | PageSize | حجم صفحة ملف PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

boolean - صحيح للنجاح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

تصنع كتيب من firstInputStream إلى outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | التدفق المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| pageSize | PageSize | حجم صفحة ملف PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

boolean - صحيح للنجاح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

تصنع كتيب من الملف المصدر وتخزن النتيجة في كائنات HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| pageSize | PageSize | حجم الصفحة المرغوب. |
| leftPages | Int32[] | مصفوفة من أرقام الصفحات التي سيتم وضعها في اليسار. |
| rightPages | Int32[] | مصفوفة من أرقام الصفحات التي سيتم وضعها في اليمين. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا كانت العملية قد نجحت.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

تصنع كتيب من ملف PDF وتخزنه في HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الوثيقة المدخل. |
| pageSize | PageSize | حجم الصفحة المرغوب. |
| leftPages | Int32[] | مصفوفة من أرقام الصفحات التي سيتم وضعها في اليسار. |
| rightPages | Int32[] | مصفوفة من أرقام الصفحات التي سيتم وضعها في اليمين. |
| response | HttpResponse | كائن HttpResponse. |

### قيمة الإرجاع

صحيح إذا كانت العملية قد نجحت.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

تصنع كتيب من الملف المصدر وتخزن النتيجة في كائنات HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| pageSize | PageSize | حجم الصفحة المرغوب في ملف الإخراج. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا كانت العملية قد نجحت.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

تصنع كتيب من الملف المصدر وتخزن النتيجة في HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الوثيقة المدخل. |
| pageSize | PageSize | حجم الصفحة المرغوب في ملف الإخراج. |
| response | HttpResponse | كائن الاستجابة حيث سيتم حفظ النتيجة. |

### قيمة الإرجاع

صحيح إذا تم بناء الكتيب بنجاح.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)