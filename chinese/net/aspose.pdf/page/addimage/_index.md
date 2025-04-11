---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Page 方法。将图像添加到页面并将其定位在指定矩形的中间，保持图像的比例
type: docs
weight: 350
url: /zh/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

将图像添加到页面并将其定位在指定矩形的中间，保持图像的比例。

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 图像的流。 |
| imageRect | Rectangle | 图像的位置。 |
| bbox | Rectangle | 图像的边界框。 |
| autoAdjustRectangle | Boolean | 将图像调整到输入矩形的中心。 |

### 另见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

将可搜索的图像添加到页面并将其定位在指定矩形的中间，保持图像的比例。

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hocr | String | 图像的 hocr。 |
| imageStream | Stream | 图像的流。 |
| imageRect | Rectangle | 图像的位置。 |
| bbox | Rectangle | 图像的边界框。 |

### 另见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

将图像添加到页面并根据图像矩形位置放置它。

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 图像的流。 |
| imageRect | Rectangle | 图像在页面上的默认位置。 |
| imageWidth | Int32 | 图像的宽度。 |
| imageHeight | Int32 | 图像的高度。 |
| saveImageProportions | Boolean | 如果标志设置为 true，则图像放置在矩形位置；否则，矩形的大小将等于图像大小。 |
| bbox | Rectangle | 图像的边界框。 |

### 另见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

将图像添加到页面并将其定位在指定矩形的中间，保持图像的比例。

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imagePath | String | 图像的路径。 |
| rectangle | Rectangle | 图像的位置。 |

### 另见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)