---
title: "类 FileSpecification"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.FileSpecification 类。表示嵌入文件的类"
type: docs
weight: 4970
url: /zh/net/aspose.pdf/filespecification/
---
## FileSpecification class

表示嵌入文件的类。

```csharp
public sealed class FileSpecification : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | 创建新的空文件规范。 |
| [FileSpecification](filespecification/#constructor_3)(string) | FileSpecification 的构造函数 |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | 文件规范的构造函数。 |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | FileSpecification 的构造函数。 |
| [FileSpecification](filespecification/#constructor_5)(string, string) | FileSpecification 的构造函数。 |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | FileSpecification 的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | 关联的文件关系。 |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | 获取文件规范的集合项。 |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | 获取或设置内容文件。此属性返回加载到内存中的数据，可能会导致大数据时出现内存不足异常。为降低内存使用，请使用 StreamContents。 |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | 获取或设置与文件规范关联的文本。 |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | 获取或设置编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。 |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | 获取加密的负载。 |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | 获取或设置文件系统的名称。 |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | 如果为 true，则文件内容将包含在文件规范中。 |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | 获取嵌入文件的子类型 |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | 获取或设置文件规范名称。 |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | 获取文件参数。 |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | 以流的形式获取文件内容。内容不会加载到内存中，从而降低内存使用。但此流不支持定位和 Length 属性。如果需要这些功能，请改用 Contents 属性。 |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | 获取或设置文件规范的 Unicode 名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | 释放内容。 |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | 获取特定于应用程序的参数。 |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | 设置特定于应用程序的参数。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


