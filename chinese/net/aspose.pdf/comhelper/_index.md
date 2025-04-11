---
title: Class ComHelper
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ComHelper class. 提供方法供 COM 客户端将文档加载到 Aspose.Pdf
type: docs
weight: 3130
url: /zh/net/aspose.pdf/comhelper/
---
## ComHelper class

提供方法供 COM 客户端将文档加载到 Aspose.Pdf。

```csharp
public class ComHelper
```

## Constructors

| Name | Description |
| --- | --- |
| [ComHelper](comhelper/)() | 默认构造函数。 |

## Methods

| Name | Description |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | 仅使用 *filename* 创建并返回 Document。与 [`Document`](../document/document/) 相同。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | 从文件打开现有文档，提供必要的转换选项以获取 pdf 文档。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | 初始化并返回用于处理加密文档的 [`Document`](../document/) 类的新实例。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | 初始化用于处理加密文档的 [`Document`](../document/) 类的新实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | 从 *input* 流初始化并返回新的 Document 实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | 从 *input* 流初始化并返回新的 Document 实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | 从流打开并返回现有文档，提供必要的转换以获取 pdf 文档。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | 从 *input* 流初始化并返回新的 Document 实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | 从 *input* 流初始化并返回新的 Document 实例。 |

## Remarks

使用 ComHelper 类从文件或流加载文档到 COM 应用程序中的 Document 对象。Document 类提供默认构造函数以创建新文档，并且还提供重载构造函数以从文件或流加载文档。如果您在 .NET 应用程序中使用 Aspose.Words，您可以直接使用所有 Document 构造函数，但如果您在 COM 应用程序中使用 Aspose.Pdf，则仅提供默认 Document 构造函数。

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)