---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metadata 类。提供对 XMP 元数据流的访问
type: docs
weight: 6950
url: /zh/net/aspose.pdf/metadata/
---
## 元数据类

提供对 XMP 元数据流的访问。

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | 获取集合中元素的数量。 |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | 获取扩展字段的字典。 |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | 检查集合是否具有固定大小。 |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | 检查集合是否为只读。 |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | 检查集合是否已同步。 |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | 获取或设置元数据中的数据。 |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | 获取元数据键的集合。 |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | 获取命名空间管理器。 |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | 获取集合同步对象。 |
| [Values](../../aspose.pdf/metadata/values/) { get; } | 获取元数据中的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | 将键值对添加到字典中。 |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | 将值添加到元数据。 |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | 将 PDF 扩展添加到元数据。 |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | 将值添加到元数据。 |
| [Clear](../../aspose.pdf/metadata/clear/)() | 清除元数据。 |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | 检查指定的键值对是否包含在字典中。 |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | 检查键是否包含在元数据中。 |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | 确定此字典是否包含指定的键。 |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | 返回字典枚举器。 |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | 根据前缀返回命名空间 URI。 |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | 根据命名空间 URI 返回前缀。 |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | 注册命名空间 URI。 |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | 注册命名空间 URI。 |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | 从集合中删除键/值对。 |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | 从元数据中删除条目。 |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | 尝试在字典中查找键，并在找到时检索值。 |

### 另见

* 类 [XmpValue](../xmpvalue/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)