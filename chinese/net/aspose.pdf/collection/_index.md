---
title: Collection
second_title: Aspose.PDF for .NET API 参考
description: 代表 Collection12.3.5 Collections 的类
type: docs
weight: 1480
url: /zh/net/aspose.pdf/collection/
---
## Collection class

代表 Collection(12.3.5 Collections) 的类。

```csharp
public class Collection : EmbeddedFileCollection
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Collection](collection)() | 初始化新的 Collection 对象。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count) { get; } | 获取集合中嵌入文件的数量。 |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry) { get; } | 默认嵌入文件名。 |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized) { get; } | 获取一个值，该值指示对该集合的访问是否是同步的（线程安全的）。 |
| [Item](../../aspose.pdf/embeddedfilecollection/item) { get; } | 通过索引获取嵌入文件。 (2 indexers) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys) { get; } | 返回文件附件键列表。 |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot) { get; } | 获取可用于同步访问此集合的对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add)(FileSpecification) | 将嵌入文件规范添加到集合中。 |
| [Add](../../aspose.pdf/embeddedfilecollection/add)(string, FileSpecification) | 将文件添加到具有指定键的嵌入文件中。 |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto)(FileSpecification[], int) | 将 FileSpecification 对象的数组复制到集合中。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete)() | 从文档中删除所有嵌入文件。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete)(string) | 按名称删除嵌入文件。 |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey)(string) | 通过集合中的键从集合中删除文件。 |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname)(string) | 按名称返回嵌入文件。 |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator)() | 返回集合枚举器。 |

### 也可以看看

* class [EmbeddedFileCollection](../embeddedfilecollection)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
