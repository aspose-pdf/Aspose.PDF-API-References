---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة الصفحة. تضيف صورة إلى الصفحة وتحدد موقعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصور
type: docs
weight: 350
url: /ar/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

تضيف صورة إلى الصفحة وتحدد موقعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | تدفق الصورة. |
| imageRect | Rectangle | موقع الصورة. |
| bbox | Rectangle | bbox للصورة. |
| autoAdjustRectangle | Boolean | ضبط الصورة في مركز المستطيل المدخل. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

تضيف صورة قابلة للبحث إلى الصفحة وتحدد موقعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hocr | String | hocr للصورة. |
| imageStream | Stream | تدفق الصورة. |
| imageRect | Rectangle | موقع الصورة. |
| bbox | Rectangle | bbox للصورة. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

تضيف صورة إلى الصفحة وتضعها بناءً على موقع مستطيل الصورة.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | تدفق الصورة. |
| imageRect | Rectangle | الموقع الافتراضي للصورة على الصفحة. |
| imageWidth | Int32 | عرض الصورة. |
| imageHeight | Int32 | ارتفاع الصورة. |
| saveImageProportions | Boolean | إذا تم تعيين العلامة على true، يتم وضع الصورة في موقع المستطيل؛ خلاف ذلك، يصبح حجم المستطيل مساوياً لحجم الصورة. |
| bbox | Rectangle | bbox للصورة. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

تضيف صورة إلى الصفحة وتحدد موقعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imagePath | String | المسار إلى الصورة. |
| rectangle | Rectangle | موقع الصورة. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)