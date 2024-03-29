---
title: Delete
second_title: Aspose.PDF لمرجع .NET API
description: حذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال  وحفظها كملف Pdf جديد.
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_2}

حذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال ، وحفظها كملف Pdf جديد.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | مسار ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة من ملف الإدخال. |
| outputFile | String | مسار ملف الإخراج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

حذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال ، وحفظها كملف Pdf جديد.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق ملف الإدخال. |
| pageNumber | Int32[] | فهرس الصفحة من ملف الإدخال. |
| outputStream | Stream | دفق ملف الإخراج. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Delete(string, int[], HttpResponse) {#delete_3}

حذف الصفحات المحددة من المستند وتخزين النتائج في كائن HttpResponse .

```csharp
public bool Delete(string inputFile, int[] pageNumber, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| pageNumber | Int32[] | مجموعة من أرقام الصفحات التي يجب حذفها. |
| response | HttpResponse | كائن الاستجابة حيث سيتم تخزين المستند الناتج. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## Delete(Stream, int[], HttpResponse) {#delete_1}

حذف الصفحات المحددة من المستند وحفظ النتيجة في كائن HttpResponse .

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | مصدر الوثيقة تيار. |
| pageNumber | Int32[] | مجموعة من أرقام الصفحات التي سيتم حذفها. |
| response | HttpResponse | كائن HttpResponse |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
