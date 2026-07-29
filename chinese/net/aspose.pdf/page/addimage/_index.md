---
title: "Page.AddImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "Page 方法。将图像添加到页面上，并将其定位在指定矩形的中间，保持图像比例。"
type: docs
weight: 350
url: /zh/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

在页面上添加图像，并将其定位在指定矩形的中间，同时保持图像的比例。

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | Stream | 图像的流。 |
| imageRect | Rectangle | 图像的位置。 |
| bbox | Rectangle | 图像的 Bbbox。 |
| autoAdjustRectangle | Boolean | 在输入矩形的中心调整图像。 |

### 另请参见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hocr | String | 图像的 hocr。 |
| imageStream | Stream | 图像的流。 |
| imageRect | Rectangle | 图像的位置。 |
| bbox | Rectangle | 图像的 bbox。 |

### 另请参见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

在页面上添加图像，并根据图像矩形的位置进行放置。

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
| saveImageProportions | Boolean | 如果将标志设置为 true，则图像放置在矩形位置；否则，矩形的大小将等于图像的尺寸。 |
| bbox | Rectangle | 图像的 bbox。 |

### 另请参见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

在页面上添加图像，并将其定位在指定矩形的中间，同时保持图像的比例。

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imagePath | String | 图像的路径。 |
| 矩形 | Rectangle | 图像的位置。 |

### 另请参见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


