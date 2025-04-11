---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineCollection 类。表示文档大纲层次结构
type: docs
weight: 8000
url: /zh/net/aspose.pdf/outlinecollection/
---
## OutlineCollection 类

表示文档大纲层次结构。

```csharp
public sealed class OutlineCollection : Outlines
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | 集合项的数量。请不要与 VisibleCount 混淆：VisibleCount 获取所有级别上可见大纲项的数量。 |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | 获取表示大纲中第一个顶级项的大纲项。 |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | 获取一个值，指示对该集合的访问是否是同步的（线程安全）。 |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | 通过索引从集合中获取大纲项。 |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | 获取表示大纲中最后一个顶级项的大纲项。 |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | 获取一个可以用于同步访问该集合的对象。 |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | 计数是所有级别上可见后代大纲项数量的总和。注意：请不要与 Count 混淆，Count 是集合中项的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | 将大纲项添加到集合中。 |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | 清除集合中的所有项。 |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | 检查集合是否包含给定项。 |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | 将大纲项复制到 System.Array，从特定的 System.Array 索引开始。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | 从文档大纲中删除所有大纲项。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | 从文档大纲中删除具有指定标题的大纲项。 |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | 返回一个枚举器，用于迭代集合。 |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | 通过索引移除项。 |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | 始终抛出 NotImplementedException |

### 另请参阅

* 类 [Outlines](../outlines/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)