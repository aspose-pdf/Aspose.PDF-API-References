---
title: LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API 参考
description: 表示转换时边距区域的使用方式 如HTMLEPUB等定义了导入格式 与边距使用相关的指令的处理方式
type: docs
weight: 3960
url: /zh/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

表示转换时边距区域的使用方式 （如HTML、EPUB等），定义了导入格式 与边距使用相关的指令的处理方式。

```csharp
public enum MarginsAreaUsageModes
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | 在此模式下，转换器遵循导入文档的格式（导入 HTML 的 fe CSS） 使用边距区域。因此，如果导入文档的格式需要使用 的边距区域进行渲染，转换器将允许使用 |
| NeverPutContentOnMarginArea | `1` | 此模式严格禁止使用边距区域， 因此，转换器永远不会使用边距区域进行渲染， 即使CSS或源文档格式允许或要求 |

### 也可以看看

* class [LoadOptions](../loadoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->