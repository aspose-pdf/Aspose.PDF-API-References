---
title: Class DocumentInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocumentInfo 类。表示 PDF 文档的元信息
type: docs
weight: 3870
url: /zh/net/aspose.pdf/documentinfo/
---
## DocumentInfo class

表示 PDF 文档的元信息。

```csharp
public sealed class DocumentInfo : Dictionary<string, string>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DocumentInfo](documentinfo/)(Document) | 初始化 DocumentInfo 实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Author](../../aspose.pdf/documentinfo/author/) { get; set; } | 获取或设置文档作者。 |
| [CreationDate](../../aspose.pdf/documentinfo/creationdate/) { get; set; } | 获取或设置文档创建日期。 |
| [CreationTimeZone](../../aspose.pdf/documentinfo/creationtimezone/) { get; set; } | 创建日期的时区。 |
| [Creator](../../aspose.pdf/documentinfo/creator/) { get; set; } | 获取或设置文档创建者。 |
| [Item](../../aspose.pdf/documentinfo/item/) { get; set; } | 获取或设置与指定键相关联的值。 |
| [Keywords](../../aspose.pdf/documentinfo/keywords/) { get; set; } | 获取或设置文档的关键字。 |
| [ModDate](../../aspose.pdf/documentinfo/moddate/) { get; set; } | 获取或设置文档修改日期。 |
| [ModTimeZone](../../aspose.pdf/documentinfo/modtimezone/) { get; set; } | 修改日期的时区。 |
| [Producer](../../aspose.pdf/documentinfo/producer/) { get; set; } | 获取或设置文档生产者。 |
| [Subject](../../aspose.pdf/documentinfo/subject/) { get; set; } | 获取或设置文档的主题。 |
| [Title](../../aspose.pdf/documentinfo/title/) { get; set; } | 获取或设置文档标题。 |
| [Trapped](../../aspose.pdf/documentinfo/trapped/) { get; set; } | 获取或设置被捕获标志。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/documentinfo/add/#add)(string, string) | 将具有指定键和值的元素添加到集合中。 |
| [Clear](../../aspose.pdf/documentinfo/clear/#clear)() | 清除文档信息。 |
| [ClearCustomData](../../aspose.pdf/documentinfo/clearcustomdata/)() | 仅清除自定义数据，保留所有其他预定义值（标题、作者等）。 |
| [Remove](../../aspose.pdf/documentinfo/remove/#remove_2)(string) | 从集合中移除具有指定键的元素。 |
| static [IsPredefinedKey](../../aspose.pdf/documentinfo/ispredefinedkey/)(string) | 确定键是否为预定义（标题、作者等），而不是自定义。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)