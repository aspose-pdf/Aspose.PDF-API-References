---
title: "类 PdfXmpMetadata"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfXmpMetadata 类。用于操作 XMP 元数据的类。"
type: docs
weight: 4760
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

用于操作 XMP 元数据的类。

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | PdfXmpMetadata 的构造函数。 |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | 在 *document* 的基础上初始化新的 `PdfXmpMetadata` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | 获取集合中项目的计数。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | 获取扩展字段的字典。 |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | 如果集合具有固定大小，则返回 true。 |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | 如果集合为只读，则返回 true。 |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | 如果集合已同步，则返回 true。 |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | 通过键获取或设置值。（2 个索引器） |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | 获取字典中的键。 |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | 获取集合的同步对象。 |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | 获取字典中的值集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | 向字典中添加键和值对。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | 向 XMP 元数据添加值。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | 向字典对象添加新元素。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | 向字典对象添加新元素。 |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | 向元数据中添加扩展字段。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化 facade。 |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | 从对象中移除所有元素。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | 检查字典是否包含指定的属性。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | 检查字典中是否包含指定的键值对。 |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | 检查字典是否包含指定的键。 |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | 确定此字典是否包含指定的键。 |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | 获取字典的枚举器对象。 |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | 通过前缀获取命名空间 URI。 |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | 通过命名空间 URI 获取前缀。 |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | 以 XML 格式获取输入 PDF 的 XmpMetadata。 |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | 根据元数据名称获取输入 PDF 的 XmpMetadata 的一部分。 |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | 注册命名空间 URI。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | 移除具有指定键的元素。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | 从集合中移除键/值对。 |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | 从字典中移除键。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将 PDF 文档保存到指定的流中。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将 PDF 文档保存到指定的文件中。 |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | 尝试在字典中查找键并在找到时检索其值。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* class [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


