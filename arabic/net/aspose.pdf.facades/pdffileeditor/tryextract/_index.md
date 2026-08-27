---
title: "PdfFileEditor.TryExtract"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تستخرج الصفحات من ملف الإدخال وتحفظها كملف Pdf جديد"
type: docs
weight: 410
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

يستخرج الصفحات من ملف الإدخال، يحفظها كملف Pdf جديد.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف Pdf الإدخال. |
| startPage | Int32 | رقم Page البداية. |
| endPage | Int32 | رقم Page النهاية. |
| outputFile | String | مسار ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، إلا أن طريقة TryExtract لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف PDF جديد.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة خارج ملف الإدخال. |
| outputFile | String | مسار ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، إلا أن طريقة TryExtract لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف Pdf جديد.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة خارج ملف الإدخال. |
| outputStream | Stream | دفق ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، إلا أن طريقة TryExtract لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


