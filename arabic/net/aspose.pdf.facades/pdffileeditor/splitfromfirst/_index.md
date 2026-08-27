---
title: "PdfFileEditor.SplitFromFirst"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد وتحفظ الجزء الأمامي كملف جديد"
type: docs
weight: 340
url: /ar/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

يقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف Pdf المصدر. |
| الموقع | Int32 | نقطة التقسيم. |
| outputFile | String | ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المصدر. |
| الموقع | Int32 | نقطة التقسيم. |
| outputStream | Stream | دفق ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## ملاحظات

التدفقات لا تُغلق بعد هذه العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


