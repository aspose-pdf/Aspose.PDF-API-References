---
title: "类 ComHelper"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.ComHelper 类。提供供 COM 客户端将 Document 加载到 Aspose.Pdf 的方法。"
type: docs
weight: 3240
url: /zh/net/aspose.pdf/comhelper/
---
## ComHelper class

提供给 COM 客户端将文档加载到 Aspose.Pdf 的方法。

```csharp
public class ComHelper
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ComHelper](comhelper/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | 只需使用 *filename* 创建并返回 Document。与 [`Document`](../document/document/) 相同。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | 从文件打开现有 Document，提供必要的转换选项以获取 pdf 文档。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | 初始化并返回用于处理加密 Document 的 [`Document`](../document/) 类的新实例。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | 初始化用于处理加密 Document 的 [`Document`](../document/) 类的新实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | 从 *input* 流初始化并返回新的 Document 实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | 从 *input* 流初始化并返回新的 Document 实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | 从流中打开并返回现有 Document，提供必要的转换以获取 pdf 文档。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | 从 *input* 流初始化并返回新的 Document 实例。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | 从 *input* 流初始化并返回新的 Document 实例。 |

## 备注

在 COM 应用程序中使用 ComHelper 类将文件或流中的 Document 加载到 Document 对象。Document 类提供默认构造函数来创建新文档，并提供重载构造函数以从文件或流加载 Document。如果在 .NET 应用程序中使用 Aspose.Words，您可以直接使用所有 Document 构造函数；但在 COM 应用程序中使用 Aspose.Pdf 时，仅可使用默认的 Document 构造函数。

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


