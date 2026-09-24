---
title: "Page.AddImage"
linktitle: "AddImage"
articleTitle: "AddImage"
second_title: "Aspose.PDF for .NET"
description: "Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion."
type: docs
weight: 170
url: "/net/aspose.pdf/page/addimage/"
product_version: "26.9.0"
---
## AddImage(Stream, [Rectangle](../../../aspose.pdf.drawing/rectangle/), [Rectangle](../../../aspose.pdf.drawing/rectangle/), bool) {#addimage}

Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox, bool autoAdjustRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | The stream of the image. |
| imageRect | Rectangle | The position of the image. |
| bbox | Rectangle | Bbox of the image. |
| autoAdjustRectangle | bool | Adjust image in center of the input rectangle. |

### See Also

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, [Rectangle](../../../aspose.pdf.drawing/rectangle/), [Rectangle](../../../aspose.pdf.drawing/rectangle/)) {#addimage_1}

Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox)
```

| Parameter | Type | Description |
| --- | --- | --- |
| hocr | string | The hocr of the image. |
| imageStream | Stream | The stream of the image. |
| imageRect | Rectangle | The position of the image. |
| bbox | Rectangle | The bbox of the image. |

### See Also

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, [Rectangle](../../../aspose.pdf.drawing/rectangle/), int, int, bool, [Rectangle](../../../aspose.pdf.drawing/rectangle/)) {#addimage_2}

Adds image on page and places it depend on image rectangle position.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, bool saveImageProportions, Rectangle bbox)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | The stream of the image. |
| imageRect | Rectangle | The default position of the image on page. |
| imageWidth | int | The width of the image. |
| imageHeight | int | The height of the image. |
| saveImageProportions | bool | If the flag set to true than image placed in rectangle position; otherwise, the size of rectange is becoming equal to image size. |
| bbox | Rectangle | The bbox of the image. |

### See Also

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, [Rectangle](../../../aspose.pdf.drawing/rectangle/)) {#addimage_3}

Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imagePath | string | The path to image. |
| rectangle | Rectangle | The position of the image. |

### See Also

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

