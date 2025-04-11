---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تستخرج الصفحات من الملفات المدخلة وتحفظ كملف Pdf جديد
type: docs
weight: 410
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

تستخرج الصفحات من الملف المدخل، وتحفظ كملف Pdf جديد.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار ملف Pdf المدخل. |
| startPage | Int32 | رقم الصفحة الابتدائية. |
| endPage | Int32 | رقم الصفحة النهائية. |
| outputFile | String | مسار ملف Pdf الناتج. |

### قيمة الإرجاع

صحيح عند النجاح، أو خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، باستثناء أن طريقة TryExtract لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

تستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، وتحفظ كملف PDF جديد.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المدخل. |
| pageNumber | Int32[] | فهرس الصفحة من الملف المدخل. |
| outputFile | String | مسار الملف الناتج. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، باستثناء أن طريقة TryExtract لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

تستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، وتحفظ كملف Pdf جديد.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الملف المدخل. |
| pageNumber | Int32[] | فهرس الصفحة من الملف المدخل. |
| outputStream | Stream | تدفق الملف الناتج. |

### قيمة الإرجاع

صحيح عند النجاح، أو خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، باستثناء أن طريقة TryExtract لا ترمي استثناء إذا فشلت العملية.

## أمثلة

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

تستخرج الصفحات المحددة من الملف المصدر وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق المستند المصدر. |
| pageNumber | Int32[] | مصفوفة أرقام الصفحات التي سيتم استخراجها. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، باستثناء أن طريقة TryExtract لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

تستخرج الصفحات المحددة من الملف المصدر وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | مسار الملف المصدر. |
| pageNumber | Int32[] | مصفوفة أرقام الصفحات التي سيتم استخراجها. |
| response | HttpResponse | كائن HttpResponse حيث سيتم تخزين النتيجة. |

### قيمة الإرجاع

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## ملاحظات

طريقة TryExtract تشبه طريقة Extract، باستثناء أن طريقة TryExtract لا ترمي استثناء إذا فشلت العملية.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)