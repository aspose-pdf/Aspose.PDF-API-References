---
title: "PdfFileEditor.Insert"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تُدرج الصفحات من ملف آخر إلى ملف Pdf في موضع معين."
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

يدرج الصفحات من ملف آخر إلى ملف Pdf في موضع معين.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف Pdf الإدخال. |
| insertLocation | Int32 | الموضع في ملف الإدخال. |
| portFile | String | ملف Pdf المنقول. |
| startPage | Int32 | الموضع الابتدائي في portFile. |
| endPage | Int32 | الموضع النهائي في portFile. |
| outputFile | String | ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الإدخال لملف Pdf. |
| insertLocation | Int32 | إدراج الموضع في ملف الإدخال. |
| portStream | Stream | دفق ملف Pdf للصفحات. |
| startPage | Int32 | من أي صفحة للبدء. |
| endPage | Int32 | إلى أي صفحة للانتهاء. |
| outputStream | Stream | دفق الإخراج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف Pdf الإدخال. |
| insertLocation | Int32 | إدراج الموضع في ملف الإدخال. |
| portFile | String | صفحات من ملف Pdf. |
| pageNumber | Int32[] | رقم الصفحة للمنقولة في portFile. |
| outputFile | String | ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الإدخال لملف Pdf. |
| insertLocation | Int32 | إدراج الموضع في ملف الإدخال. |
| portStream | Stream | دفق ملف Pdf للصفحات. |
| pageNumber | Int32[] | رقم الصفحة للمنقولة في portFile. |
| outputStream | Stream | دفق الإخراج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


