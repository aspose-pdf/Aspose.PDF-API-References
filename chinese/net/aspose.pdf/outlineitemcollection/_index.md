---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineItemCollection 类。表示 PDF 文档大纲层次结构中的大纲条目
type: docs
weight: 8010
url: /zh/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection 类

表示 PDF 文档大纲层次结构中的大纲条目。

```csharp
public sealed class OutlineItemCollection : Outlines
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | 使用根层次结构对象初始化大纲项实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | 获取或设置此大纲项的操作。 |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | 获取或设置此大纲项标题文本的粗体标志 |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | 获取或设置此大纲项标题文本的颜色。 |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | 集合项的计数。请不要与 VisibleCount 混淆：VisibleCount 获取所有级别上可见的大纲项数量。 |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | 获取或设置此大纲项的目标。 |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | 获取表示大纲层次结构中第一个顶级项的大纲项。 |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | 检查大纲项是否表示相对于此项的下一个项。 |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | 获取一个值，指示对该集合的访问是否是同步的（线程安全）。 |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | 获取或设置此大纲项标题文本的斜体标志 |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | 使用索引从集合中获取大纲项。 |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | 获取表示大纲层次结构中最后一个顶级项的大纲项。 |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | 获取大纲项的层次级别。 |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | 获取表示相对于此项的下一个项的大纲项。 |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | 获取或设置大纲项的打开状态（true/false）。 |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | 获取此大纲项在大纲层次结构中的父对象。 |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | 获取表示相对于此项的前一个项的大纲项。 |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | 获取可用于同步访问该集合的对象。 |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | 获取或设置此大纲项的标题。 |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | 获取文档大纲层次结构中所有级别的大纲项的总数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | 将大纲项添加到集合。 |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | 清除集合中的所有项。 |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | 检查集合是否包含给定项。 |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | 将大纲条目复制到 System.Array，从特定的 System.Array 索引开始。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | 从文档大纲层次结构中删除此大纲项。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | 从文档大纲层次结构中删除具有指定名称的大纲条目。 |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | 返回一个枚举器，用于迭代集合。 |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | 在指定位置将大纲项插入集合。 |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | 按索引移除项。 |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | 移除大纲集合项。 |

### 另请参阅

* 类 [Outlines](../outlines/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)