---
title: ComHelper
second_title: Aspose.PDF for .NET API 参考
description: 为 COM 客户端提供将文档加载到 Aspose.Pdf. 的方法
type: docs
weight: 1540
url: /zh/net/aspose.pdf/comhelper/
---
## ComHelper class

为 COM 客户端提供将文档加载到 Aspose.Pdf. 的方法

```csharp
public class ComHelper
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ComHelper](comhelper)() | 默认构造函数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile#openfile)(string) | 只需创建并返回 Document 使用*filename*.一样[`Document`](../document/document). |
| [OpenFile](../../aspose.pdf/comhelper/openfile#openfile_1)(string, LoadOptions) | 从提供必要转换选项的文件中打开现有文档以获取 pdf 文档。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile#openfile_2)(string, string) | 初始化并返回[`Document`](../document)用于处理加密文档的类。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile#openfile_3)(string, string, bool) | 初始化新实例[`Document`](../document)用于处理加密文档的类。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream#openstream)(Stream) | 初始化并从*input*流. |
| [OpenStream](../../aspose.pdf/comhelper/openstream#openstream_2)(Stream, bool) | 初始化并从*input*流. |
| [OpenStream](../../aspose.pdf/comhelper/openstream#openstream_1)(Stream, LoadOptions) | 打开并从流中返回现有文档，提供必要的转换以获取 pdf 文档。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream#openstream_3)(Stream, string) | 初始化并从*input*流. |
| [OpenStream](../../aspose.pdf/comhelper/openstream#openstream_4)(Stream, string, bool) | 初始化并从*input*流. |

### 评论

使用 ComHelper 类将文档从文件或流加载到 COM 应用程序中的 Document 对象中。 Document 类提供默认构造函数以创建新文档 并提供重载构造函数以从文件或流加载文档. 如果您在 .NET 应用程序中使用 Aspose.Words，则可以直接使用所有 Document 构造函数，但如果您在 COM 应用程序中使用 Aspose.Pdf， 只有默认的 Document 构造函数可用。

### 也可以看看

* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->