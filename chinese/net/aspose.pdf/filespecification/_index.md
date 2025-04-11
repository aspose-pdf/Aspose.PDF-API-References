---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification 类。表示嵌入文件的类
type: docs
weight: 4850
url: /zh/net/aspose.pdf/filespecification/
---
## FileSpecification class

表示嵌入文件的类。

```csharp
public sealed class FileSpecification : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | 创建新的空文件规范。 |
| [FileSpecification](filespecification/#constructor_3)(string) | FileSpecification 的构造函数 |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | 文件规范的构造函数。 |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | FileSpecification 的构造函数。 |
| [FileSpecification](filespecification/#constructor_5)(string, string) | FileSpecification 的构造函数。 |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | FileSpecification 的构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | 关联文件关系。 |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | 获取文件规范的集合项。 |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | 获取或设置内容文件。此属性返回加载到内存中的数据，可能会导致大数据的内存不足异常。要减少内存使用，请使用 StreamContents。 |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | 获取或设置与文件规范相关的文本。 |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | 获取或设置编码格式。可能的值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。 |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | 获取加密负载。 |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | 获取或设置文件系统的名称。 |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | 如果为 true，文件的内容将包含在文件规范中。 |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | 获取嵌入文件的子类型 |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | 获取或设置文件规范名称。 |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | 获取文件参数。 |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | 获取文件的内容作为流。内容未加载到内存中，这样可以减少内存使用。但此流不支持定位和 Length 属性。如果您需要这些功能，请使用 Contents 属性。 |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | 获取或设置文件规范的 Unicode 名称。 |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | 释放内容。 |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | 获取特定于应用程序的参数。 |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | 设置特定于应用程序的参数。 |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)