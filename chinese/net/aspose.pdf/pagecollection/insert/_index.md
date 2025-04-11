---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: PageCollection 方法。将一个空页面插入到指定位置的集合中。如果文档已经包含不同大小的页面，将选择出现频率最高的页面的大小。如果只有两个不同的页面，将使用第一个页面的大小。
type: docs
weight: 160
url: /zh/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

将一个空页面插入到指定位置的集合中。如果文档已经包含不同大小的页面，将选择出现频率最高的页面的大小。如果只有两个不同的页面，将使用第一个页面的大小。

```csharp
public Page Insert(int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 新页面的位置。 |

### 返回值

插入的页面。

### 另见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

在指定位置将页面插入到页面集合中。

```csharp
public Page Insert(int pageNumber, Page entity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 集合中所需的页面索引。 |
| entity | Page | 要插入的页面。 |

### 返回值

插入的页面。

### 另见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

将集合中的页面插入到文档中。

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 新页面的起始位置。 |
| pages | ICollection`1 | 页面集合。 |

### 另见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

将数组中的页面插入到文档中。

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 新页面的起始编号。 |
| pages | Page[] | 将要插入的页面数组。 |

### 另见

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)