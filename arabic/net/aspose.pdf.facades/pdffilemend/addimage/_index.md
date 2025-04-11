---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileMend. تضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

تضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | تدفق الصورة المدخلة. |
| pageNum | Int32 | رقم الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

تضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | تدفق الصورة المدخلة. |
| pageNum | Int32 | رقم الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تجميع الرسوميات للصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

تضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | تدفق الصورة المدخلة. |
| pageNums | Int32[] | أرقام الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

تضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | تدفق الصورة المدخلة. |
| pageNums | Int32[] | أرقام الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تجميع الرسوميات للصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

تضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخلة. |
| pageNum | Int32 | رقم الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

تضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخلة. |
| pageNum | Int32 | رقم الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تجميع الرسوميات للصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

تضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخلة. |
| pageNums | Int32[] | أرقام الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### See Also

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

تضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخلة. |
| pageNums | Int32[] | أرقام الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي السيني السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي الصادي السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي السيني العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي الصادي العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تجميع الرسوميات للصورة. |

### Return Value

صحيح إذا نجح، خطأ خلاف ذلك.

## Examples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### See Also

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)