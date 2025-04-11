---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptionsRecognitionMode 枚举。当通常具有固定布局的 PDF 文件被转换时，转换引擎尝试执行分组和多级分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性调整该转换以适应所需的内容识别方法。
type: docs
weight: 4070
url: /zh/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode 枚举

当 PDF 文件（通常具有固定布局）被转换时，转换引擎尝试执行分组和多级分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性调整该转换以适应所需的内容识别方法。

```csharp
public enum RecognitionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Flow | `0` | 完全识别模式，引擎尝试执行分组和多级分析，以恢复原始文档作者的意图并生成流式布局的 xhtml。 |
| PdfFlow | `1` | 此转换的主要思想是基于保存处理 PDF 文档时形成的内容渲染的“自然”顺序。在一般情况下，PDF 文档保持自上而下、自左而右的渲染顺序（请参见附件 directions.png）。这个假设允许创建一个单路径算法，将具有位置（固定布局）的 Aps 元素转换为 HTML、EPUB、DOC 等流格式。此模式在从 PDF（APS）转换为 EPUB 时特别有用，因为 EPUB 格式是为 Kindle 或智能手机等电子阅读器开发的。这些设备的屏幕大小通常小于普通 PC 的屏幕大小。因此，EPUB 文档的内容最好以流格式保存，以便在不同大小的屏幕上正确渲染。在此模式下，每一列将添加到前一列的末尾，这允许在 EPUB 阅读器中“分页”时保持转换文档的逻辑结构。这一成就允许正确渲染科学或杂志文章。 |
| Fixed | `2` | 此模式快速且适合最大限度地保留原始页面的外观，但不幸的是，许多 EPUB 阅读器不支持具有固定布局的 xhtml。 |

### 另请参阅

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)