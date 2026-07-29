---
title: "枚举 EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.EpubSaveOptionsRecognitionMode 枚举。当将通常具有固定布局的 PDF 文件转换时，转换引擎会尝试进行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性用于调节内容识别的具体方式。"
type: docs
weight: 4190
url: /zh/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试进行分组和多层次分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性用于针对不同的内容识别方法微调该转换。

```csharp
public enum RecognitionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Flow | `0` | 完整识别模式，引擎尝试进行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的 XHTML。 |
| PdfFlow | `1` | 此转换的主要思路是保存 PDF 文档处理过程中形成的“自然”内容渲染顺序。一般情况下，PDF 文档保持自上而下、从左到右的渲染顺序（参见附件 directions.png）。该假设使得可以创建单一路径算法，将具有位置（固定布局）的 Aps 元素转换为 HTML、EPUB、DOC 等流式格式。此模式在将 PDF（APS）转换为 EPUB 时尤为有用，因为 EPUB 格式是为 Kindle 或智能手机等电子阅读器设计的。这些设备的屏幕尺寸通常小于普通 PC 的屏幕尺寸。因此，EPUB 文档的内容更适合以流式格式保存，以便在不同尺寸的屏幕上正确渲染。在此模式下，每一列会被添加到前一列的末尾，从而在 EPUB 阅读器的“分页”过程中保持转换后文档的逻辑结构。此实现能够正确渲染科学或杂志文章。 |
| Fixed | `2` | 此模式快速且有助于最大程度保留原始页面外观，但遗憾的是许多 EPUB 阅读器不支持带固定布局的 XHTML。 |

### 另请参见

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


