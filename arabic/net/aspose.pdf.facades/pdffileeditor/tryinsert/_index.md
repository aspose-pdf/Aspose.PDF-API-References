---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تُدرج صفحات من ملف آخر في ملف Pdf المدخل
type: docs
weight: 420
url: /ar/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

تُدرج صفحات من ملف آخر في ملف Pdf المدخل.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المدخل. |
| insertLocation | Int32 | موضع الإدراج في الملف المدخل. |
| portFile | String | صفحات من ملف Pdf. |
| pageNumber | Int32[] | رقم الصفحة المنقولة في portFile. |
| outputFile | String | ملف Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Remarks

طريقة TryInsert تشبه طريقة Insert، باستثناء أن طريقة TryInsert لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

تُدرج صفحات من ملف آخر في ملف Pdf المدخل.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المدخل. |
| insertLocation | Int32 | موضع الإدراج في الملف المدخل. |
| portStream | Stream | تدفق ملف Pdf للصفحات. |
| pageNumber | Int32[] | رقم الصفحة المنقولة في portFile. |
| outputStream | Stream | تدفق الناتج. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TryInsert تشبه طريقة Insert، باستثناء أن طريقة TryInsert لا ترمي استثناء إذا فشلت العملية.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

تُدرج محتويات الملف في الملف المصدر وتخزن النتيجة في كائن HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | اسم الملف المصدر. |
| insertLocation | Int32 | رقم الصفحة التي سيتم إدراج الملف الثاني فيها. |
| portFile | String | مسار الملف الذي سيتم إدراجه. |
| pageNumber | Int32[] | مصفوفة أرقام الصفحات في الملف المصدر التي سيتم إدراجها. |
| response | HttpResponse | كائن الاستجابة حيث سيتم تخزين النتيجة. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TryInsert تشبه طريقة Insert، باستثناء أن طريقة TryInsert لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

تُدرج مستندًا في مستند آخر وتخزن النتيجة في كائن الاستجابة.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق مع المستند المصدر |
| insertLocation | Int32 | الموقع الذي سيتم إدراج المستند الآخر فيه. |
| portStream | Stream | المستند الذي سيتم إدراجه. |
| pageNumber | Int32[] | مصفوفة أرقام الصفحات في المستند الثاني التي سيتم إدراجها. |
| response | HttpResponse | كائن الاستجابة حيث سيتم تخزين النتيجة. |

### Return Value

صحيح إذا اكتملت العملية بنجاح؛ خلاف ذلك، خطأ.

## Remarks

طريقة TryInsert تشبه طريقة Insert، باستثناء أن طريقة TryInsert لا ترمي استثناء إذا فشلت العملية.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)