---
title: Insert
second_title: Aspose.PDF لمرجع .NET API
description: يقوم بإدراج صفحات من ملف آخر في ملف Pdf في موضع ما.
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

يقوم بإدراج صفحات من ملف آخر في ملف Pdf في موضع ما.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال ملف PDF. |
| insertLocation | Int32 | ضع في ملف الإدخال. |
| portFile | String | ملف Pdf الذي يتم نقله. |
| startPage | Int32 | بدء الموقف في portFile. |
| endPage | Int32 | الموضع النهائي في portFile. |
| outputFile | String | إخراج ملف PDF. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق الإدخال لملف Pdf. |
| insertLocation | Int32 | أدخل الموضع في ملف الإدخال. |
| portStream | Stream | دفق ملف PDF للصفحات. |
| startPage | Int32 | من أي صفحة تبدأ. |
| endPage | Int32 | إلى أي صفحة تنتهي. |
| outputStream | Stream | تيار الإخراج. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال ملف PDF. |
| insertLocation | Int32 | أدخل الموضع في ملف الإدخال. |
| portFile | String | صفحات من ملف Pdf. |
| pageNumber | Int32[] | رقم صفحة الملف المنفذ في المنفذ. |
| outputFile | String | إخراج ملف PDF. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق الإدخال لملف Pdf. |
| insertLocation | Int32 | أدخل الموضع في ملف الإدخال. |
| portStream | Stream | دفق ملف PDF للصفحات. |
| pageNumber | Int32[] | رقم صفحة الملف المنفذ في المنفذ. |
| outputStream | Stream | تيار الإخراج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

إدراج محتويات الملف في الملف المصدر وتخزين النتائج في كائن HttpResponse .

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | اسم الملف المصدر. |
| insertLocation | Int32 | رقم الصفحة حيث سيتم إدراج الملف الثاني. |
| portFile | String | مسار الملف الذي سيتم إدراجه. |
| pageNumber | Int32[] | مجموعة من أرقام الصفحات في الملف المصدر التي سيتم إدراجها. |
| response | HttpResponse | كائن الاستجابة حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح أن الإدخال كان ناجحًا.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

إدراج المستند في مستند آخر وتخزين النتائج في كائن استجابة.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق مع المستند المصدر |
| insertLocation | Int32 | الموقع حيث سيتم إدراج المستند الآخر. |
| portStream | Stream | الوثيقة المراد ادراجها. |
| pageNumber | Int32[] | مجموعة من أرقام الصفحات في المستند الثاني والتي سيتم إدراجها. |
| response | HttpResponse | كائن الاستجابة حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
