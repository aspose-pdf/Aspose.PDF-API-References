---
title: "PdfFileMend.AddImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileMend. تضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة"
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | دفق صورة الإدخال. |
| pageNum | Int32 | عدد الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### انظر أيضًا

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | دفق صورة الإدخال. |
| pageNum | Int32 | عدد الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تركيب الرسومات للصورة. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### انظر أيضًا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | دفق صورة الإدخال. |
| pageNums | Int32[] | عدد الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### انظر أيضًا

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | دفق صورة الإدخال. |
| pageNums | Int32[] | عدد الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تركيب الرسومات للصور. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### انظر أيضًا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخل. |
| pageNum | Int32 | عدد الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### انظر أيضًا

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخل. |
| pageNum | Int32 | عدد الصفحة التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تركيب الرسومات للصور. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### انظر أيضًا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخل. |
| pageNums | Int32[] | عدد الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### انظر أيضًا

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageName | String | مسار ملف الصورة المدخل. |
| pageNums | Int32[] | عدد الصفحات التي ستستقبل الصورة. |
| lowerLeftX | Single | الإحداثي x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | الإحداثي y السفلي الأيسر لمستطيل الصورة. |
| upperRightX | Single | الإحداثي x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | الإحداثي y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تركيب الرسومات للصور. |

### قيمة الإرجاع

صحيح إذا نجح، غير ذلك خطأ.

## أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### انظر أيضًا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


