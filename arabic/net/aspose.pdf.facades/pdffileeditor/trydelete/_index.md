---
title: "PdfFileEditor.TryDelete"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال وتحفظها كملف Pdf جديد."
type: docs
weight: 400
url: /ar/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة خارج ملف الإدخال. |
| outputFile | String | مسار ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ وإلا، خطأ.

## ملاحظات

طريقة TryDelete تشبه طريقة Delete، إلا أن طريقة TryDelete لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة خارج ملف الإدخال. |
| outputStream | Stream | دفق ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

طريقة TryDelete تشبه طريقة Delete، إلا أن طريقة TryDelete لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


