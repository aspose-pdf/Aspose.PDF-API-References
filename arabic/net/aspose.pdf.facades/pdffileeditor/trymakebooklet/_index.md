---
title: "PdfFileEditor.TryMakeBooklet"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تُنشئ كتيّبًا من الملف الإدخال إلى ملف الإخراج"
type: docs
weight: 430
url: /ar/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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

ينشئ كتيبًا من InputStream إلى outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الإدخال. |
| outputStream | Stream | دفق pdf الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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

ينشئ كتيبًا من inputFile إلى outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار واسم ملف pdf الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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

ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق PDF الإدخال. |
| outputStream | Stream | دفق pdf الإخراج. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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

ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| leftPages | Int32[] | الصفحات اليسرى للكتاب المصغر. |
| rightPages | Int32[] | الصفحات اليمنى للكتاب المصغر. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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

ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق الإدخال. |
| outputStream | Stream | دفق pdf الإخراج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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

ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف الإدخال. |
| outputFile | String | مسار واسم ملف pdf الإخراج. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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

ينشئ كتيبًا من firstInputStream إلى outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق الإدخال. |
| outputStream | Stream | دفق pdf الإخراج. |
| pageSize | PageSize | حجم الصفحة لملف pdf الإخراج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات اليمنى. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryMakeBooklet تشبه طريقة MakeBooklet، إلا أن طريقة TryMakeBooklet لا تُطلق استثناءً إذا فشلت العملية.

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


