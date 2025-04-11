---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode 枚举。允许控制 PDF 文档如何转换为文字处理文档
type: docs
weight: 3770
url: /zh/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode 枚举

允许控制 PDF 文档如何转换为文字处理文档。

```csharp
public enum RecognitionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Textbox | `0` | 此模式快速且适合最大限度地保留 PDF 文件的原始外观，但生成文档的可编辑性可能有限。 |
| Flow | `1` | 完全识别模式，引擎执行分组和多级分析，以恢复原始文档作者的意图并生成最大限度可编辑的文档。缺点是输出文档可能与原始 PDF 文件看起来不同。 |
| EnhancedFlow | `2` | 支持表格识别的替代 Flow 模式。 |

## 备注

当生成的文档不打算进一步进行大量编辑时，请使用 Textbox 模式。当需要进行较少修改时，文本框易于修改。

当输出文档需要进一步编辑时，请使用 Flow 模式。Flow 模式中的段落和文本行允许轻松修改文本，但不支持的格式对象在 Textbox 模式下的外观会更差。

### 另见

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)