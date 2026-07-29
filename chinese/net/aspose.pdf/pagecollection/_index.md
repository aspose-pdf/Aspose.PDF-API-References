---
title: "类 PageCollection"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PageCollection 类。PDF 文档页面的集合"
type: docs
weight: 8220
url: /zh/net/aspose.pdf/pagecollection/
---
## PageCollection class

PDF 文档页面的集合。

```csharp
public sealed class PageCollection : ICollection<Page>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | 获取文档中页面的数量。 |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | 获取指示集合是否为只读的值。始终返回 false。 |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | 如果对象已同步则返回 true。 |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | 按索引获取页面。 |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | 获取集合的同步对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | 接受 [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) 访问者对象，提供处理注释的功能。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | 接受 [`ImagePlacementAbsorber`](../imageplacementabsorber/) 访问者对象，提供处理图像放置对象的功能。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | 接受 [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) 访问者对象，提供处理文本对象的功能。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | 接受 [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) 访问者对象，提供处理文本对象的功能。 |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | 添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若仅有两种不同的页面，则使用第一页的尺寸。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | 将列表中的所有页面添加到集合中。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | 将页面添加到集合中。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | 将数组中的所有页面添加到集合中。 |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | 清除页面集合。 |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | 确定此实例是否包含该对象。 |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | 将页面复制到文档中。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | 从集合中删除所有页面。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | 删除指定页面。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | 删除数组中指定编号的页面。 |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | 移除页面上所有字段，并将其值放置在原处。 |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | 清除缓存数据 |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | 返回页面的枚举器。 |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | 返回指定页面的索引。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | 在指定位置向集合中插入一个空白页面。如果文档已经包含尺寸不同的页面，则选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | 将集合中的页面插入文档。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | 在指定位置将页面插入页面集合。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | 将数组中的页面插入文档。 |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | 移除指定项，抛出 NotSupportedException。 |

### 另请参见

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


