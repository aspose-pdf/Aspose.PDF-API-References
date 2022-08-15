---
title: TryMakeNUp
second_title: Aspose.PDF لمرجع .NET API
description: جعل مستند N-up والمخازن ينتج عنه كائن HttpResponse .
type: docs
weight: 470
url: /ar/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, int, int, PageSize, HttpResponse) {#trymakenup_6}

جعل مستند N-up والمخازن ينتج عنه كائن HttpResponse .

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة في ملف النتيجة. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

جعل مستند N-up والمخازن ينتج عنه كائن HttpResponse .

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق المستند المصدر. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة في ملف النتيجة. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

يجعل مستند N-up والمخازن ينتج عنه HttpResponse .

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | اسم الملف المصدر. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

يجعل المستندات والمخازن N-up تؤدي إلى HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق وثيقة الإدخال. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| response | HttpResponse | HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

يجعل مستند N-Up من firstInputFile إلى ملف الإخراج.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال اسم ومسار ملف pdf. |
| outputFile | String | إخراج مسار ملف pdf واسمه. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### قيمة الإرجاع

صحيح إذا تمت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_2}

يجعل مستند N-Up من دفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | إدخال تيار pdf . |
| outputStream | Stream | إخراج pdf stream. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_3}

يجعل مستند N-Up من دفق الإدخال الأول إلى تدفق الإخراج.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | إدخال تيار pdf . |
| outputStream | Stream | إخراج pdf stream. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_10}

يجعل مستند N-Up من ملفي PDF للإدخال إلى ملف الإخراج. ستحتوي كل صفحة من ملف الإخراج على صفحتين ، صفحة واحدة من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. الصفحتان مكدمتان أفقيًا.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstInputFile | String | ملف الإدخال الأول. |
| secondInputFile | String | ملف الإدخال الثاني. |
| outputFile | String | إخراج مسار ملف pdf واسمه. |

### قيمة الإرجاع

صحيح إذا تمت العملية بنجاح خلاف ذلك ، خطأ

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

يجعل مستند N-Up من دفقتي PDF للإدخال إلى outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstInputStream | Stream | تيار الإدخال الأول. |
| secondInputStream | Stream | تيار الإدخال الثاني. |
| outputStream | Stream | إخراج pdf stream. |

### قيمة الإرجاع

صحيح إذا تمت العملية بنجاح خلاف ذلك ، خطأ

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_11}

يجعل مستند N-Up من ملفات PDF متعددة المدخلات إلى ملف الإخراج. ستحتوي كل صفحة من ملف الإخراج على صفحات متعددة ، والتي يتم دمجها مع الصفحات في ملفات الإدخال لنفس رقم الصفحة. الصفحات المتعددة المكدسة أفقيًا إذا كان الجانب الآخر صحيحًا ومكدسة عموديًا إذا كان العرض الجانبي خاطئًا.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFiles | String[] | إدخال ملفات Pdf. |
| outputFile | String | إخراج مسار ملف pdf واسمه. |
| isSidewise | Boolean | الطريقة المكدسة ، صحيحة بالنسبة للأفقي والخطأ للعمودي. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_5}

يجعل مستند N-Up من تدفقات PDF متعددة المدخلات إلى outputStream . ستحتوي كل صفحة من تدفق الإخراج على صفحات متعددة ، والتي يتم دمجها مع صفحات في تدفقات الإدخال لنفس رقم الصفحة. الصفحات المتعددة المكدسة أفقيًا إذا كان الجانب الآخر صحيحًا ومكدسة عموديًا إذا كان العرض الجانبي خاطئًا.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStreams | Stream[] | تيارات Pdf الإدخال. |
| outputStream | Stream | إخراج دفق pdf. |
| isSidewise | Boolean | الطريقة المكدسة ، صحيحة بالنسبة للأفقي والخطأ للعمودي. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_9}

يجعل مستند N-Up من ملف الإدخال إلى ملف الإخراج.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال اسم ومسار ملف pdf. |
| outputFile | String | إخراج مسار ملف pdf واسمه. |
| x | Int32 | عدد الأعمدة. |
| y | Int32 | عدد الصفوف. |
| pageSize | PageSize | حجم الصفحة لملف pdf الناتج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح خلاف ذلك ، خطأ.

### ملاحظات

تشبه طريقة TryMakeNUp طريقة MakeNUp ، باستثناء أن طريقة TryMakeNUp لا تطرح استثناءً إذا فشلت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
