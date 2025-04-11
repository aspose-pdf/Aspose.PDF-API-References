---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection 方法。将新图像添加到图像列表。此方法将图像作为对同一 PdfObject 的引用添加，从而减少文件大小
type: docs
weight: 70
url: /zh/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

将新图像添加到图像列表。此方法将图像作为对同一 PdfObject 的引用添加（这允许减少文件大小）

```csharp
public string Add(XImage image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | XImage | 要添加的 XImage。 |

### 返回值

添加的图像名称。

### 另见

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public string Add(Stream image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | Stream | 包含图像数据的流（JPEG 格式）。 |

### 返回值

添加的图像名称。

### 另见

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | 包含像素数组和位图信息（宽度、高度、像素格式）的对象。 |

### 返回值

添加的图像名称。

### 另见

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | Stream | 包含图像数据的流。 |
| filterType | ImageFilterType | 图像过滤器类型。 |

### 返回值

添加的图像名称。

### 另见

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | 包含像素数组和位图信息（宽度、高度、像素格式）的对象。 |
| filterType | ImageFilterType | 图像过滤器类型。 |

### 返回值

添加的图像名称。

### 另见

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public void Add(Stream image, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | Stream | 包含图像数据的流（JPEG 格式）。 |
| quality | Int32 | JPEG 质量。 |

### 另见

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)