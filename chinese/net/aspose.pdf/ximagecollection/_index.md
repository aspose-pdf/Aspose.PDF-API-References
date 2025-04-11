---
title: Class XImageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImageCollection class. 类表示 XImage 集合
type: docs
weight: 11360
url: /zh/net/aspose.pdf/ximagecollection/
---
## XImageCollection class

类表示 XImage 集合。

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | 集合中图像的数量。 |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | 如果对象是同步的，则返回 true。 |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | 通过索引从集合中获取图像。 (2 个索引器) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | 获取图像名称的数组。 |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | 返回同步对象。 |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | 将实体添加到集合的末尾，以便可以通过最后一个索引访问实体。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | 将实体添加到集合的末尾，以便可以通过最后一个索引访问实体。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | 将新图像添加到图像列表。此方法将图像作为对同一 PdfObject 的引用添加（这允许减少文件大小） |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | 将实体添加到集合的末尾，以便可以通过最后一个索引访问实体。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | 将实体添加到集合的末尾，以便可以通过最后一个索引访问实体。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | 将实体添加到集合的末尾，以便可以通过最后一个索引访问实体。 |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | 清除集合中的所有项。 |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | 确定集合是否包含特定值。 |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | 将图像数组复制到集合中。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | 从集合中删除图像。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | 通过索引从集合中移除索引。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | 通过名称从集合中移除项。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | 通过索引从集合中移除图像，执行由操作参数指定的操作。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | 通过名称从集合中移除项。 |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | 返回集合枚举器。 |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | 返回图像列表中给定图像的名称。 |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | 从集合中移除项，抛出 NotImplementedException。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | 用另一幅图像替换集合中的图像。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | 用另一幅图像替换集合中的图像。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | 用另一幅图像替换集合中的图像。 |

### See Also

* class [XImage](../ximage/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)