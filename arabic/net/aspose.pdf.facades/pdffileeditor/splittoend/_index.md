---
title: "PdfFileEditor.SplitToEnd"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تقسم من الموقع وتحفظ الجزء الخلفي كملف جديد."
type: docs
weight: 360
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream جديد.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المصدر. |
| الموقع | Int32 | موضع التقسيم. |
| outputStream | Stream | تدفق ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

التدفقات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف Pdf المصدر. |
| الموقع | Int32 | موضع التقسيم. |
| outputFile | String | مسار ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream جديد.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المصدر. |
| الموقع | Int32 | موضع التقسيم. |
| outputStream | Stream | تدفق ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

التدفقات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


