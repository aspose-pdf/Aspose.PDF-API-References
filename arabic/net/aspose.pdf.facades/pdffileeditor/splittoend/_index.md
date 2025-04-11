---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تقسم من الموقع وتخزن الجزء الخلفي كملف جديد
type: docs
weight: 360
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

تقسم من الموقع المحدد، وتخزن الجزء الخلفي كملف جديد من نوع Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | مصدر ملف Pdf من نوع Stream. |
| location | Int32 | موضع التقسيم. |
| outputStream | Stream | ملف Pdf الناتج من نوع Stream. |

### Return Value

صحيح للنجاح، أو خطأ.

## Remarks

التيارات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

تقسم من الموقع، وتخزن الجزء الخلفي كملف جديد.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المصدر. |
| location | Int32 | موضع التقسيم. |
| outputFile | String | مسار ملف Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

تقسم من الموقع المحدد، وتخزن الجزء الخلفي كملف جديد من نوع Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | مصدر ملف Pdf من نوع Stream. |
| location | Int32 | موضع التقسيم. |
| outputStream | Stream | ملف Pdf الناتج من نوع Stream. |

### Return Value

صحيح للنجاح، أو خطأ.

## Remarks

التيارات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)