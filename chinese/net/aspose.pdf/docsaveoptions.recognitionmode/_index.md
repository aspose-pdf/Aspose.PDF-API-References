---
title: "枚举 DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.DocSaveOptionsRecognitionMode 枚举。允许控制 PDF 文档如何转换为文字处理文档。"
type: docs
weight: 3890
url: /zh/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

允许控制 PDF 文档如何转换为文字处理文档。

```csharp
public enum RecognitionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Textbox | `0` | 此模式快速且能够最大程度保留 PDF 文件的原始外观，但生成文档的可编辑性可能受限。 |
| Flow | `1` | 完整识别模式，引擎执行分组和多层分析以恢复原始文档作者的意图并生成可最大程度编辑的文档。缺点是输出文档可能与原始 PDF 文件的外观不同。 |
| EnhancedFlow | `2` | 一种支持表格识别的替代 Flow 模式。 |

## 备注

当生成的文档不需要大量后续编辑时，请使用 Textbox 模式。文本框在修改工作量不大时易于修改。

当输出文档需要进一步编辑时，请使用 Flow 模式。Flow 模式中的段落和文本行便于文本的修改，但不受支持的格式对象的显示效果会比 Textbox 模式更差。

### 另请参见

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


