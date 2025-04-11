---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.IOperationResult 接口。定义具体插件操作结果应实现的通用操作结果接口
type: docs
weight: 8850
url: /zh/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult 接口

定义具体插件操作结果应实现的通用操作结果接口。

```csharp
public interface IOperationResult
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | 获取原始数据。 |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | 指示结果是否为输出文件的路径。 |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | 指示结果是否为输出流。 |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | 指示结果是否为文本字符串。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | 尝试将结果转换为文件。 |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | 尝试将结果转换为流对象。 |

### 另见

* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)