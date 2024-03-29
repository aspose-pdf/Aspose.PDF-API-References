---
title: SplitToEnd
second_title: Aspose.PDF لمرجع .NET API
description: ينقسم عن الموقع ويحفظ الجزء الخلفي كملف جديد.
type: docs
weight: 390
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_2}

ينقسم عن الموقع ويحفظ الجزء الخلفي كملف جديد.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | ملف PDF المصدر. |
| location | Int32 | موقف الانقسام. |
| outputFile | String | إخراج مسار ملف Pdf. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

ينقسم عن الموقع المحدد ، ويحفظ الجزء الخلفي كملف جديد.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | مصدر ملف Pdf دفق. |
| location | Int32 | موقف الانقسام. |
| outputStream | Stream | إخراج ملف Pdf دفق. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### ملاحظات

لا يتم إغلاق التدفقات بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams.

### أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, HttpResponse) {#splittoend_1}

ينقسم من الموقع المحدد ، ويحفظ الجزء الخلفي في كائن HttpResponse .

```csharp
public bool SplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | مصدر الوثيقة تيار. |
| location | Int32 | نقطة الانقسام. |
| response | HttpResponse | كائن HttpResponse. |

### قيمة الإرجاع

صحيح إذا كان التقسيم ناجحًا.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, HttpResponse) {#splittoend_3}

ينقسم من الموقع المحدد ، ويحفظ الجزء الخلفي في كائن HttpResponse .

```csharp
public bool SplitToEnd(string inputFile, int location, HttpResponse response)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | اسم الملف المصدر. |
| location | Int32 | نقطة الانقسام. |
| response | HttpResponse | كائنات HttpResponse. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
