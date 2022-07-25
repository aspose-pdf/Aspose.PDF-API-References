---
title: AddImage
second_title: Aspose.PDF لمرجع .NET API
description: يضيف الصورة إلى الصفحة المحددة من مستند PDF بالإحداثيات المحددة.
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

يضيف الصورة إلى الصفحة المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageStream | Stream | إدخال دفق الصورة. |
| pageNum | Int32 | رقم الصفحة التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### أنظر أيضا

* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

يضيف الصورة إلى الصفحة المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageStream | Stream | إدخال دفق الصورة. |
| pageNum | Int32 | رقم الصفحة التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تكوين الرسومات للصورة. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### أنظر أيضا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

إضافة صورة إلى الصفحات المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageStream | Stream | إدخال دفق الصورة. |
| pageNums | Int32[] | عدد الصفحات التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### أنظر أيضا

* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

إضافة صورة إلى الصفحات المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageStream | Stream | إدخال دفق الصورة. |
| pageNums | Int32[] | عدد الصفحات التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تكوين الرسومات للصور. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### أنظر أيضا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

يضيف الصورة إلى الصفحة المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageName | String | مسار ملف صورة الإدخال. |
| pageNum | Int32 | رقم الصفحة التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### أنظر أيضا

* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

يضيف الصورة إلى الصفحة المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageName | String | مسار ملف صورة الإدخال. |
| pageNum | Int32 | رقم الصفحة التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تكوين الرسومات للصور. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### أنظر أيضا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

إضافة صورة إلى الصفحات المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageName | String | مسار ملف صورة الإدخال. |
| pageNums | Int32[] | عدد الصفحات التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### أنظر أيضا

* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

إضافة صورة إلى الصفحات المحددة من مستند PDF بالإحداثيات المحددة.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageName | String | مسار ملف صورة الإدخال. |
| pageNums | Int32[] | عدد الصفحات التي ستتلقى الصورة. |
| lowerLeftX | Single | x السفلي الأيسر لمستطيل الصورة. |
| lowerLeftY | Single | أسفل يسار ص لمستطيل الصورة. |
| upperRightX | Single | x العلوي الأيمن لمستطيل الصورة. |
| upperRightY | Single | y العلوي الأيمن لمستطيل الصورة. |
| compositingParameters | CompositingParameters | معلمات تكوين الرسومات للصور. |

### قيمة الإرجاع

صحيح إذا كان النجاح خاطئًا بخلاف ذلك.

### أمثلة

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### أنظر أيضا

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilemend)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
