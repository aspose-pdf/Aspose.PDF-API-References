---
title: "Page.AddImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Page. تضيف صورة إلى الصفحة وتضعها في وسط المستطيل المحدد مع الحفاظ على نسبة أبعاد الصورة."
type: docs
weight: 350
url: /ar/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | دفق الصورة. |
| imageRect | Rectangle | موضع الصورة. |
| bbox | Rectangle | Bbox للصورة. |
| autoAdjustRectangle | Boolean | ضبط الصورة في مركز المستطيل المدخل. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| hocr | String | hocr للصورة. |
| imageStream | Stream | دفق الصورة. |
| imageRect | Rectangle | موضع الصورة. |
| bbox | Rectangle | Bbox للصورة. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

يضيف صورة إلى الصفحة ويضعها اعتمادًا على موضع مستطيل الصورة.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | دفق الصورة. |
| imageRect | Rectangle | الموضع الافتراضي للصورة على الصفحة. |
| imageWidth | Int32 | عرض الصورة. |
| imageHeight | Int32 | ارتفاع الصورة. |
| saveImageProportions | Boolean | إذا تم تعيين العلامة إلى true فإن الصورة توضع في موضع المستطيل؛ وإلا يصبح حجم المستطيل مساويًا لحجم الصورة. |
| bbox | Rectangle | Bbox للصورة. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imagePath | String | المسار إلى الصورة. |
| مستطيل | Rectangle | موضع الصورة. |

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


