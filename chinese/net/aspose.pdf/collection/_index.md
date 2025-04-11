---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Collection 类。表示 Collection12.3.5 集合的类
type: docs
weight: 3020
url: /zh/net/aspose.pdf/collection/
---
## 集合类

表示 Collection(12.3.5 集合) 的类。

```csharp
public class Collection : EmbeddedFileCollection
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Collection](collection/)() | 初始化新的 Collection 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | 获取集合中嵌入文件的数量。 |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | 默认嵌入文件名称。 |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | 获取一个值，指示访问此集合是否是同步的（线程安全）。 |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | 通过索引获取嵌入文件。 (2 个索引器) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | 返回文件附件键的列表。 |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | 获取文档集合的“模式”。 |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | 获取一个可以用于同步访问此集合的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | 将嵌入文件规范添加到集合中。 |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | 使用指定的键将文件添加到嵌入文件中。 |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | 将 FileSpecification 对象数组复制到集合中。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | 从文档中删除所有嵌入文件。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | 按名称删除嵌入文件。 |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | 按集合中的键从集合中删除文件。 |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | 按名称返回嵌入文件。 |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | 返回集合枚举器。 |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | 获取按规范排序的文件集合。 |

### 另见

* 类 [EmbeddedFileCollection](../embeddedfilecollection/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)