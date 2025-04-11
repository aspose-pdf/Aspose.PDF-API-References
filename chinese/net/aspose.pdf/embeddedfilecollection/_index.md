---
title: Class EmbeddedFileCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EmbeddedFileCollection 类。表示嵌入文件集合的类
type: docs
weight: 4010
url: /zh/net/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection 类

表示嵌入文件集合的类。

```csharp
public class EmbeddedFileCollection : ICollection<FileSpecification>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | 获取集合中嵌入文件的数量。 |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | 获取一个值，指示访问此集合是否是同步的（线程安全）。 |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | 通过索引获取嵌入文件。（2 个索引器） |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | 返回文件附件键的列表。 |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | 获取一个可以用于同步访问此集合的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add)(FileSpecification) | 将嵌入文件规范添加到集合中。 |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add_1)(string, FileSpecification) | 使用指定的键将文件添加到嵌入文件中。 |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | 将 FileSpecification 对象数组复制到集合中。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete)() | 从文档中删除所有嵌入文件。 |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete_1)(string) | 按名称删除嵌入文件。 |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | 按集合中的键从集合中删除文件。 |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | 按名称返回嵌入文件。 |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | 返回集合枚举器。 |

### 另请参阅

* 类 [FileSpecification](../filespecification/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)