---
title: "PdfFileEditor.TryInsert"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تُدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال"
type: docs
weight: 420
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

## ملاحظات

طريقة TryInsert تشبه طريقة Insert، إلا أن طريقة TryInsert لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryInsert تشبه طريقة Insert، إلا أن طريقة TryInsert لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


