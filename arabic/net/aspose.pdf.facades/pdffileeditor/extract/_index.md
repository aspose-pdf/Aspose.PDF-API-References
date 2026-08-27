---
title: "PdfFileEditor.Extract"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تستخرج الصفحات من ملف الإدخال وتحفظها كملف Pdf جديد"
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

يستخرج الصفحات من ملف الإدخال، يحفظها كملف Pdf جديد.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف Pdf الإدخال. |
| startPage | Int32 | رقم Page البداية. |
| endPage | Int32 | رقم Page النهاية. |
| outputFile | String | مسار ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف PDF جديد.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة خارج ملف الإدخال. |
| outputFile | String | مسار ملف الإخراج. |

### قيمة الإرجاع

True إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

يستخرج الصفحات من ملف الإدخال، يحفظها كملف Pdf جديد.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق ملف الإدخال. |
| startPage | Int32 | رقم Page البداية. |
| endPage | Int32 | رقم Page النهاية. |
| outputStream | Stream | تدفق ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف Pdf جديد.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة خارج ملف الإدخال. |
| outputStream | Stream | دفق ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


