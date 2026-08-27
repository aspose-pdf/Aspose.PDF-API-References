---
title: "类 OutlineCollection"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.OutlineCollection 类。表示文档大纲层次结构"
type: docs
weight: 8140
url: /zh/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

表示文档大纲层次结构。

```csharp
public sealed class OutlineCollection : Outlines
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | 集合项的计数。请不要与 VisibleCount 混淆：VisibleCount 获取所有层级中可见大纲项的数量。 |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | 获取表示大纲中第一个顶层项的大纲项。 |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | 获取一个值，指示对该集合的访问是否已同步（线程安全）。 |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | 通过索引从集合中获取大纲项。 |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | 获取表示大纲中最后一个顶层项的大纲项。 |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | 获取可用于同步对该集合访问的对象。 |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Count 是所有层级中可见子大纲项数量的总和。注意：请不要将其与集合中项的数量 Count 混淆。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | 向集合中添加大纲项。 |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | 清除集合中的所有项。 |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | 检查集合是否包含给定的项。 |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | 将大纲项复制到 System.Array 中，从特定的 System.Array 索引开始。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | 从文档大纲中删除所有大纲项。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | 从文档大纲中删除具有指定标题的大纲项。 |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | 按索引移除项。 |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | 始终抛出 NotImplementedException。 |

### 另请参见

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


