---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تصنع كتيب من ملف الإدخال إلى ملف الإخراج
type: docs
weight: 430
url: /ar/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

تصنع كتيب من ملف المصدر وتخزن النتيجة في كائنات HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف المصدر. |
| pageSize | PageSize | حجم الصفحة المطلوب. |
| leftPages | Int32[] | مصفوفة من أرقام الصفحات التي ستوضع في اليسار. |
| rightPages | Int32[] | مصفوفة من أرقام الصفحات التي ستوضع في اليمين. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

تصنع كتيب من ملف PDF وتخزنه في HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الوثيقة المدخلة. |
| pageSize | PageSize | حجم الصفحة المطلوب. |
| leftPages | Int32[] | مصفوفة من أرقام الصفحات التي ستوضع في اليسار. |
| rightPages | Int32[] | مصفوفة من أرقام الصفحات التي ستوضع في اليمين. |
| response | HttpResponse | كائن HttpResponse. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

تصنع كتيب من ملف المصدر وتخزن النتيجة في كائنات HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف المصدر. |
| pageSize | PageSize | حجم الصفحة المطلوب في ملف الإخراج. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

True إذا نجحت العملية.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

تصنع كتيب من ملف المصدر وتخزن النتيجة في HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الوثيقة المدخلة. |
| pageSize | PageSize | حجم الصفحة المطلوب في ملف الإخراج. |
| response | HttpResponse | كائن الاستجابة حيث سيتم حفظ النتيجة. |

### قيمة الإرجاع

true إذا تم بناء الكتيب بنجاح.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

تصنع كتيب من ملف الإدخال إلى ملف الإخراج.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف PDF المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

تصنع كتيب من InputStream إلى outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

تصنع كتيب من inputFile إلى outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف PDF المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| pageSize | PageSize | حجم الصفحة لملف PDF الناتج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

تصنع كتيب من تدفق الإدخال وتخزن النتيجة في تدفق الإخراج.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق PDF المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| pageSize | PageSize | حجم الصفحة لملف PDF الناتج. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

تصنع كتيب مخصص من firstInputFile إلى outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | الملف المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى من الكتيب. |
| rightPages | Int32[] | الصفحات اليمنى من الكتيب. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

تصنع كتيب مخصص من firstInputStream إلى outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | التدفق المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

تصنع كتيب مخصص من firstInputFile إلى outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | الملف المدخل. |
| outputFile | String | مسار واسم ملف PDF الناتج. |
| pageSize | PageSize | حجم الصفحة لملف PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

تصنع كتيب من firstInputStream إلى outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | التدفق المدخل. |
| outputStream | Stream | تدفق PDF الناتج. |
| pageSize | PageSize | حجم الصفحة لملف PDF الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

true إذا اكتملت العملية بنجاح؛ خلاف ذلك، false.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، باستثناء أن طريقة TryMakeBooklet لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)