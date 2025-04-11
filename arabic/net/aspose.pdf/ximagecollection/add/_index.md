---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: طريقة XImageCollection. تضيف صورة جديدة إلى قائمة الصور. تضيف هذه الطريقة الصورة كمرجع إلى نفس PdfObject مما يسمح بتقليل حجم الملف
type: docs
weight: 70
url: /ar/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

تضيف صورة جديدة إلى قائمة الصور. تضيف هذه الطريقة الصورة كمرجع إلى نفس PdfObject (مما يسمح بتقليل حجم الملف)

```csharp
public string Add(XImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | XImage | XImage ليتم إضافتها. |

### Return Value

اسم الصورة المضافة.

### See Also

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

تضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان بواسطة الفهرس الأخير.

```csharp
public string Add(Stream image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream يحتوي على بيانات الصورة (بتنسيق JPEG). |

### Return Value

اسم الصورة المضافة.

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

تضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان بواسطة الفهرس الأخير.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | كائن يحتوي على مصفوفة من البكسلات ومعلومات الصورة النقطية (العرض، الارتفاع، تنسيق البكسل). |

### Return Value

اسم الصورة المضافة.

### See Also

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

تضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان بواسطة الفهرس الأخير.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream يحتوي على بيانات الصورة. |
| filterType | ImageFilterType | نوع فلتر الصورة. |

### Return Value

اسم الصورة المضافة.

### See Also

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

تضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان بواسطة الفهرس الأخير.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | كائن يحتوي على مصفوفة من البكسلات ومعلومات الصورة النقطية (العرض، الارتفاع، تنسيق البكسل). |
| filterType | ImageFilterType | نوع فلتر الصورة. |

### Return Value

اسم الصورة المضافة.

### See Also

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

تضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان بواسطة الفهرس الأخير.

```csharp
public void Add(Stream image, int quality)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream يحتوي على بيانات الصورة (بتنسيق JPEG). |
| quality | Int32 | جودة JPEG. |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)