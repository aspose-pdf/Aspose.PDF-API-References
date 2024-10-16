---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Page method. Adds image onto the page and locates it in the middle of specified rectangle saving images proportion
type: docs
weight: 350
url: /net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle) {#addimage}

Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | The stream of the image. |
| imageRect | Rectangle | The position of the image. |
| bbox | Rectangle | Bbox of the image. |

### See Also

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| hocr | String | The hocr of the image. |
| imageStream | Stream | The stream of the image. |
| imageRect | Rectangle | The position of the image. |
| bbox | Rectangle | The bbox of the image. |

### See Also

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Adds image on page and places it depend on image rectangle position.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | The stream of the image. |
| imageRect | Rectangle | The default position of the image on page. |
| imageWidth | Int32 | The width of the image. |
| imageHeight | Int32 | The height of the image. |
| saveImageProportions | Boolean | If the flag set to true than image placed in rectangle position; otherwise, the size of rectange is becoming equal to image size. |
| bbox | Rectangle | The bbox of the image. |

### See Also

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imagePath | String | The path to image. |
| rectangle | Rectangle | The position of the image. |

### See Also

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


