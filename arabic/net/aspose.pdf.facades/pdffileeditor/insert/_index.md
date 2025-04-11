---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تُدرج الصفحات من ملف آخر في ملف Pdf في موقع معين
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

تُدرج الصفحات من ملف آخر في ملف Pdf في موقع معين.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المدخل. |
| insertLocation | Int32 | الموقع في ملف المدخل. |
| portFile | String | ملف Pdf المنقول. |
| startPage | Int32 | موقع البداية في portFile. |
| endPage | Int32 | موقع النهاية في portFile. |
| outputFile | String | ملف Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

تُدرج الصفحات من ملف آخر في ملف Pdf المدخل.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المدخل. |
| insertLocation | Int32 | موقع الإدراج في ملف المدخل. |
| portStream | Stream | تدفق ملف Pdf للصفحات. |
| startPage | Int32 | من أي صفحة تبدأ. |
| endPage | Int32 | إلى أي صفحة تنتهي. |
| outputStream | Stream | تدفق الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

تُدرج الصفحات من ملف آخر في ملف Pdf المدخل.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف Pdf المدخل. |
| insertLocation | Int32 | موقع الإدراج في ملف المدخل. |
| portFile | String | الصفحات من ملف Pdf. |
| pageNumber | Int32[] | رقم الصفحة المنقولة في portFile. |
| outputFile | String | ملف Pdf الناتج. |

### Return Value

صحيح للنجاح، أو خطأ.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

تُدرج الصفحات من ملف آخر في ملف Pdf المدخل.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق ملف Pdf المدخل. |
| insertLocation | Int32 | موقع الإدراج في ملف المدخل. |
| portStream | Stream | تدفق ملف Pdf للصفحات. |
| pageNumber | Int32[] | رقم الصفحة المنقولة في portFile. |
| outputStream | Stream | تدفق الناتج. |

### Return Value

صحيح إذا كانت العملية ناجحة.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)