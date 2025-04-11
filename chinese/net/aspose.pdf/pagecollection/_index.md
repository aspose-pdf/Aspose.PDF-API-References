---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageCollection 类。PDF 文档页面的集合
type: docs
weight: 8080
url: /zh/net/aspose.pdf/pagecollection/
---
## PageCollection 类

PDF 文档页面的集合。

```csharp
public sealed class PageCollection : ICollection<Page>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | 获取文档中的页面数量。 |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | 获取指示集合是否为只读的值。始终返回 false。 |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | 如果对象是同步的，则返回 true。 |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | 通过索引获取页面。 |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | 获取集合的同步对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | 接受 [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) 访问者对象，该对象提供与注释一起工作的功能。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | 接受 [`ImagePlacementAbsorber`](../imageplacementabsorber/) 访问者对象，该对象提供与图像放置对象一起工作的功能。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | 接受 [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) 访问者对象，该对象提供与文本对象一起工作的功能。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | 接受 [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) 访问者对象，该对象提供与文本对象一起工作的功能。 |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | 添加一个空页面。如果文档已经包含不同大小的页面，将选择出现频率最高的页面的大小。如果只有两个不同的页面，将使用第一个页面的大小。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | 将列表中的所有页面添加到集合中。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | 将页面添加到集合中。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | 将数组中的所有页面添加到集合中。 |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | 清除页面集合。 |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | 确定此实例是否包含该对象。 |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | 将页面复制到文档中。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | 从集合中删除所有页面。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | 删除指定页面。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | 删除数组中指定的页面。 |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | 移除页面上所有字段并替换为其值。 |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | 清除缓存数据 |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | 返回页面的枚举器。 |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | 返回指定页面的索引。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | 在指定位置向集合中插入一个空页面。如果文档已经包含不同大小的页面，将选择出现频率最高的页面的大小。如果只有两个不同的页面，将使用第一个页面的大小。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | 将集合中的页面插入到文档中。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | 在指定位置将页面插入到页面集合中。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | 将数组中的页面插入到文档中。 |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | 移除指定项，抛出 NotSupportedException。 |

### 另见

* 类 [Page](../page/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)