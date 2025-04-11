---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال وتحفظ كملف Pdf جديد
type: docs
weight: 270
url: /ar/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

تحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، وتحفظ كملف Pdf جديد.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | مسار ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة من ملف الإدخال. |
| outputFile | String | مسار ملف الإخراج. |

### Return Value

True إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

تحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، وتحفظ كملف Pdf جديد.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة من ملف الإدخال. |
| outputStream | Stream | تدفق ملف الإخراج. |

### Return Value

True للنجاح، أو false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)