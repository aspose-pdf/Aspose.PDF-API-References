---
title: "PageCollection.Insert"
second_title: "Aspose.PDF for .NET API 参考"
description: "PageCollection 方法。在指定位置向集合中插入一个空白页。如果文档已经包含尺寸不同的页面，则选择出现频率最高的页面尺寸。如果只有两种不同的页面，则使用第一页的尺寸。"
type: docs
weight: 160
url: /zh/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

在指定位置向集合中插入一个空白页面。如果文档已经包含尺寸不同的页面，则选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。

```csharp
public Page Insert(int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 新页面的位置。 |

### 返回值

已插入的页面。

### 另请参见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

在指定位置将页面插入页面集合。

```csharp
public Page Insert(int pageNumber, Page entity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 集合中所需的页面索引。 |
| 实体 | 页面 | 待插入的页面。 |

### 返回值

已插入的页面。

### 另请参见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

将集合中的页面插入文档。

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 新页面的起始位置。 |
| 页面 | ICollection`1 | 页面集合。 |

### 另请参见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

将数组中的页面插入文档。

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 新页面的起始编号。 |
| 页面 | Page[] | 将要插入的页面数组。 |

### 另请参见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


