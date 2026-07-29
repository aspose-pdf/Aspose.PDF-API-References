---
title: "类 OutlineItemCollection"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.OutlineItemCollection 类。表示 PDF 文档大纲层次结构中的大纲条目"
type: docs
weight: 8150
url: /zh/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

表示 PDF 文档大纲层次结构中的大纲条目。

```csharp
public sealed class OutlineItemCollection : Outlines
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | 使用根层次对象初始化大纲项实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | 获取或设置此大纲项的操作。 |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | 获取或设置此大纲项标题文本的粗体标志 |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | 获取或设置此大纲项标题文本的颜色。 |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | 集合项的计数。请不要与 VisibleCount 混淆：VisibleCount 获取所有层级中可见大纲项的数量。 |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | 获取或设置此大纲项的目标。 |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | 获取表示大纲层次结构中第一个顶级项的大纲项。 |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | 检查大纲项在大纲层级中相对于此项表示的下一个项。 |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | 获取指示对该集合的访问是否同步（线程安全）的值。 |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | 获取或设置此大纲项标题文本的斜体标志。 |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | 使用索引从集合中获取大纲项。 |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | 获取在大纲层级中表示最后一个顶层项的大纲项。 |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | 获取大纲项的层级级别。 |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | 获取在大纲层级中相对于此项表示的下一个大纲项。 |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | 获取或设置大纲项的打开状态（true/false）。 |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | 获取在大纲层级中此大纲项的父对象。 |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | 获取在大纲层级中相对于此项表示的前一个大纲项。 |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | 获取可用于同步对该集合访问的对象。 |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | 获取或设置此大纲项的标题。 |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | 获取 Document 大纲层级中所有层级的大纲项总数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | 向集合中添加大纲项。 |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | 清除集合中的所有项。 |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | 检查集合是否包含给定的项。 |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | 将大纲条目复制到 System.Array 中，从特定的 System.Array 索引开始。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | 从 Document 大纲层级中删除此大纲项。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | 从 Document 大纲层级中删除具有指定名称的大纲条目。 |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | 在指定位置将大纲项插入集合中。 |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | 按索引移除项。 |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | 移除大纲集合项。 |

### 另请参见

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


