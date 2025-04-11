---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد وتقوم بحفظ الجزء الأمامي كملف جديد
type: docs
weight: 340
url: /ar/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

تقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد، وتقوم بحفظ الجزء الأمامي كملف جديد.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المصدر. |
| location | Int32 | نقطة التقسيم. |
| outputFile | String | ملف Pdf الناتج. |

### Return Value

True للنجاح، أو false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

تقسم من البداية إلى الموقع المحدد، وتقوم بحفظ الجزء الأمامي في تدفق الإخراج.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المصدر. |
| location | Int32 | نقطة التقسيم. |
| outputStream | Stream | تدفق ملف الإخراج. |

### Return Value

True للنجاح، أو false.

## Remarks

التدفقات لا تُغلق بعد هذه العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)