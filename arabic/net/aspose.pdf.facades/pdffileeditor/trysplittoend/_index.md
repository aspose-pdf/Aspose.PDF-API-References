---
title: "PdfFileEditor.TrySplitToEnd"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تقسم من الموقع وتحفظ الجزء الخلفي كملف جديد."
type: docs
weight: 470
url: /ar/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف Pdf المصدر. |
| الموقع | Int32 | موضع التقسيم. |
| outputFile | String | مسار ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

طريقة TrySplitToEnd تشبه طريقة SplitToEnd، إلا أن طريقة TrySplitToEnd لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream جديد.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المصدر. |
| الموقع | Int32 | موضع التقسيم. |
| outputStream | Stream | تدفق ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

التدفقات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams. طريقة TrySplitToEnd تشبه طريقة SplitToEnd، إلا أن طريقة TrySplitToEnd لا تُطلق استثناءً إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


