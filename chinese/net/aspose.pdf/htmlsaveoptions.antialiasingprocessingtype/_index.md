---
title: "枚举 HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType 枚举。此枚举描述转换期间可能的抗锯齿措施。"
type: docs
weight: 5700
url: /zh/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

此枚举描述转换期间可能的抗锯齿措施。

```csharp
public enum AntialiasingProcessingType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | 未使用特殊的抗锯齿处理。这是针对绝大多数文档的最佳选项，且在转换期间不需要额外时间。 |
| TryCorrectResultHtml | `1` | 在这种情况下，转换器会尝试检测相邻背景图形元素的位置，并以相应方式校正生成的 HTML。此选项可提升包含由多个相邻图形元素构成的背景的文档的导出结果（对于此类文档，PDF 渲染器，例如 Acrobat Reader，通常在渲染时尝试平滑元素的边界。使用此选项，转换器模拟 PDF 渲染器的此行为）。此选项可改善某些特定文档（使用此类复合背景）的导出布局，但会增加额外的处理时间（通常约为额外时间的 10-15%）。因此，在一般情况下不建议使用此模式。 |

### 另请参见

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


