---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType 枚举。该枚举描述了转换过程中可能的抗锯齿措施
type: docs
weight: 5570
url: /zh/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType 枚举

该枚举描述了转换过程中可能的抗锯齿措施

```csharp
public enum AntialiasingProcessingType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | 不使用特殊的抗锯齿处理。这是绝大多数文档的最佳选项，并且在转换过程中不需要额外的时间 |
| TryCorrectResultHtml | `1` | 在这种情况下，转换器尝试检测具有相邻背景图形元素的位置，并以相关方式修正结果 HTML。此选项允许增强包含由多个相邻图形元素构成的背景的文档的导出结果（对于此类文档，PDF 渲染器，例如 Acrobat Reader，通常在渲染时尝试平滑元素的边界。使用此选项，转换器模拟 PDF 渲染器的行为。此选项允许增强某些特定文档（使用此类复合背景）的导出结果布局，但它需要额外的处理时间（通常约为 10-15% 的额外时间）。因此，在一般情况下不推荐使用此模式。 |

### 另请参阅

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)