---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection method. Adds new image to Image list. This method adds image as reference to the same PdfObject which allows to decrease file size
type: docs
weight: 70
url: /net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size)

```csharp
public string Add(XImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | XImage | XImage to be added. |

### Return Value

Name of the added image.

### See Also

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(Stream image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream containing image data (in JPEG format). |

### Return Value

Name of the added image.

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Object containing array of pixels and bitmap information (Width, Height, PixelFormat). |

### Return Value

Name of the added image.

### See Also

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream containing image data. |
| filterType | ImageFilterType | The image filter type. |

### Return Value

Name of the added image.

### See Also

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Object containing array of pixels and bitmap information (Width, Height, PixelFormat). |
| filterType | ImageFilterType | The image filter type. |

### Return Value

Name of the added image.

### See Also

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public void Add(Stream image, int quality)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream containing image data (in JPEG format). |
| quality | Int32 | JPEG quality. |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


