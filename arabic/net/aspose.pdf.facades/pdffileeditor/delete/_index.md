---
title: "PdfFileEditor.Delete"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال وتحفظها كملف Pdf جديد."
type: docs
weight: 270
url: /ar/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
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
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
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
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


