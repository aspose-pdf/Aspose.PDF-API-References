---
title: TryMakeBooklet
second_title: Aspose.PDF لمرجع .NET API
description: يجعل الكتيب من الملف المصدر والمخازن ينتج عنه كائنات HttpResponse .
type: docs
weight: 460
url: /ar/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

يجعل الكتيب من الملف المصدر والمخازن ينتج عنه كائنات HttpResponse .

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| pageSize | PageSize | حجم الصفحة المطلوب. |
| leftPages | Int32[] | مجموعة من أرقام الصفحات التي سيتم وضعها في اليسار. |
| rightPages | Int32[] | مجموعة من أرقام الصفحات التي سيتم وضعها في اليمين. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

إنشاء كتيب من ملف PDF وتخزينه في HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق وثيقة الإدخال. |
| pageSize | PageSize | حجم الصفحة المطلوب. |
| leftPages | Int32[] | مجموعة من أرقام الصفحات التي سيتم وضعها في اليسار. |
| rightPages | Int32[] | مجموعة من أرقام الصفحات التي سيتم وضعها في اليسار. |
| response | HttpResponse | كائن HttpResponse. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

يجعل الكتيب من الملف المصدر والمخازن ينتج عنه كائنات HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| pageSize | PageSize | حجم الصفحة المطلوب في ملف الإخراج. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

يجعل الكتيب من الملف المصدر والمخازن ينتج عنه HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق وثيقة الإدخال. |
| pageSize | PageSize | حجم الصفحة المطلوب في ملف الإخراج. |
| response | HttpResponse | وضع الكائن حيث سيتم حفظ resut. |

### قيمة الإرجاع

صحيح إذا تم بناء الكتيب بنجاح.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

يجعل الكتيب من ملف الإدخال إلى ملف الإخراج.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال اسم ومسار ملف pdf. |
| outputFile | String | إخراج مسار ملف pdf واسمه. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

يجعل كتيب من InputStream لإخراج البث .

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | إدخال تيار pdf . |
| outputStream | Stream | إخراج pdf stream. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

يجعل الكتيب من ملف الإدخال إلى ملف الإخراج.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال اسم ومسار ملف pdf. |
| outputFile | String | إخراج مسار ملف pdf واسمه. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

يجعل كتيب من دفق الإدخال وحفظ النتيجة في دفق الإخراج.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق إدخال PDF . |
| outputStream | Stream | إخراج pdf stream. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

إنشاء كتيب مخصص من ملف الإدخال الأول إلى ملف الإخراج.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | ملف الإدخال. |
| outputFile | String | مسار ملف pdf الناتج واسمه. |
| leftPages | Int32[] | الصفحات اليسرى من الكتيب. |
| rightPages | Int32[] | الصفحات الصحيحة من الكتيب. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

إنشاء كتيب مخصص من أول إدخال إلى بث الإخراج.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | تيار الإدخال. |
| outputStream | Stream | إخراج قوات الدفاع الشعبي تيار. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات الصحيحة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

إنشاء كتيب مخصص من ملف الإدخال الأول إلى ملف الإخراج.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | ملف الإدخال. |
| outputFile | String | مسار ملف pdf الناتج واسمه. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات الصحيحة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

يجعل الكتيب من أول InputStream إلى outputStream .

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | تيار الإدخال. |
| outputStream | Stream | إخراج قوات الدفاع الشعبي تيار. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |
| leftPages | Int32[] | الصفحات اليسرى. |
| rightPages | Int32[] | الصفحات الصحيحة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

طريقة TryMakeBooklet مثل طريقة MakeBooklet ، باستثناء أن طريقة TryMakeBooklet لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
