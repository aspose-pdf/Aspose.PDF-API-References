---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfXmpMetadata 类。用于操作 XMP 元数据的类
type: docs
weight: 4640
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata 类

用于操作 XMP 元数据的类。

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | PdfXmpMetadata 的构造函数。 |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfXmpMetadata` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | 获取集合中项目的数量。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | 获取扩展字段的字典。 |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | 如果集合具有固定大小，则返回 true。 |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | 如果集合是只读的，则返回 true。 |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | 如果集合是同步的，则返回 true。 |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | 通过键获取或设置值。 (2 个索引器) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | 从字典中获取键。 |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | 获取集合的同步对象。 |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | 获取字典中值的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | 将键值对添加到字典中。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | 将值添加到 XMP 元数据。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | 将新元素添加到字典对象。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | 将新元素添加到字典对象。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | 将扩展字段添加到元数据中。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | 从对象中移除所有元素。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | 检查字典是否包含指定属性。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | 检查字典中是否包含指定的键值对。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | 检查字典是否包含指定的键。 |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | 确定此字典是否包含指定的键。 |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放外观。 |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | 获取字典的枚举器对象。 |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | 根据前缀获取命名空间 URI。 |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | 根据命名空间 URI 获取前缀。 |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | 以 XML 格式获取输入 PDF 的 XmpMetadata。 |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | 根据元名称获取输入 PDF 的 XmpMetadata 的一部分。 |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | 注册命名空间 URI。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | 移除具有指定键的元素。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | 从集合中移除键/值对。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | 从字典中移除键。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将 PDF 文档保存到指定的流。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将 PDF 文档保存到指定的文件。 |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | 尝试在字典中查找键，并在找到时检索值。 |

### 另请参阅

* 类 [SaveableFacade](../saveablefacade/)
* 类 [XmpValue](../../aspose.pdf/xmpvalue/)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)