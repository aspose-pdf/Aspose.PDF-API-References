---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تستخرج الصفحات من الملفات المدخلة وتحفظ كملف Pdf جديد
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

تستخرج الصفحات من الملف المدخل، وتحفظ كملف Pdf جديد.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار ملف Pdf المدخل. |
| startPage | Int32 | رقم الصفحة الابتدائية. |
| endPage | Int32 | رقم الصفحة النهائية. |
| outputFile | String | مسار ملف Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

تستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، وتحفظ كملف PDF جديد.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار الملف المدخل. |
| pageNumber | Int32[] | فهرس الصفحة من الملف المدخل. |
| outputFile | String | مسار الملف الناتج. |

### Return Value

صحيح إذا كانت العملية قد نجحت.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

تستخرج الصفحات من الملف المدخل، وتحفظ كملف Pdf جديد.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق الملف المدخل. |
| startPage | Int32 | رقم الصفحة الابتدائية. |
| endPage | Int32 | رقم الصفحة النهائية. |
| outputStream | Stream | تدفق ملف Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

تستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، وتحفظ كملف Pdf جديد.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق الملف المدخل. |
| pageNumber | Int32[] | فهرس الصفحة من الملف المدخل. |
| outputStream | Stream | تدفق الملف الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)