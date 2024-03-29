---
title: Add
second_title: Aspose.PDF for .NET API 参考
description: 将新图像添加到图像列表此方法添加图像作为对相同 PdfObject 的引用允许减小文件大小
type: docs
weight: 70
url: /zh/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add}

将新图像添加到图像列表。此方法添加图像作为对相同 PdfObject 的引用（允许减小文件大小）

```csharp
public string Add(XImage image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | XImage | 要添加的 XImage。 |

### 返回值

添加的图像的名称。

### 也可以看看

* class [XImage](../../ximage)
* class [XImageCollection](../../ximagecollection)
* 命名空间 [Aspose.Pdf](../../ximagecollection)
* 部件 [Aspose.PDF](../../../)

---

## Add(Stream) {#add_1}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public string Add(Stream image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Stream | 包含图像数据的流（JPEG 格式）。 |

### 返回值

添加的图像的名称。

### 也可以看看

* class [XImageCollection](../../ximagecollection)
* 命名空间 [Aspose.Pdf](../../ximagecollection)
* 部件 [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_2}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public void Add(Stream image, ImageFilterType filterType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Stream | 包含图像数据的流。 |
| filterType | ImageFilterType | 图像过滤器类型。 |

### 也可以看看

* enum [ImageFilterType](../../imagefiltertype)
* class [XImageCollection](../../ximagecollection)
* 命名空间 [Aspose.Pdf](../../ximagecollection)
* 部件 [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_3}

将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

```csharp
public void Add(Stream image, int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Stream | 包含图像数据的流（JPEG 格式）。 |
| quality | Int32 | JPEG 质量。 |

### 也可以看看

* class [XImageCollection](../../ximagecollection)
* 命名空间 [Aspose.Pdf](../../ximagecollection)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
