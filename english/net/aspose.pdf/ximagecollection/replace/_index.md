---
title: "XImageCollection.Replace"
linktitle: "Replace"
articleTitle: "Replace"
second_title: "Aspose.PDF for .NET API Reference"
description: "XImageCollection method. Replace image in collection with another image."
type: docs
weight: 140
url: "/net/aspose.pdf/ximagecollection/replace/"
product_version: "26.9.0"
---
## Replace(int, Stream) {#replace}

Replace image in collection with another image.

```csharp
public void Replace(int index, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of collection item which will be replaced in [1..images count] range. |
| stream | Stream | Stream containing image data (in JPEG format). |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_1}

Replace image in collection with another image.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of collection item which will be replaced in [1..images count] range. |
| stream | Stream | Stream containing image data (in JPEG format). |
| quality | int | Quality of JPEG compression, in percent (valid vaues are 0..100). |
| isBlackAndWhite | bool | If true, image is compressed with CCITT compression method which provides better compression for black nad white image. May be used only for black and white images. |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_2}

Replace image in collection with another image.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of collection item which will be replaced in [1..images count] range. |
| stream | Stream | Stream containing image data (in JPEG format). |
| quality | int | JPEG quality. |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

