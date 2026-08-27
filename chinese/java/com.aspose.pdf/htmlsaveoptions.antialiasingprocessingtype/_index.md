---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF for Java API 参考"
description: "此枚举描述了转换过程中可能的抗锯齿措施"
type: docs
weight: 2000
url: /zh/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

此枚举描述了转换过程中可能的抗锯齿措施

## 字段

| 字段 | 描述 |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | 未使用特殊的抗锯齿处理。这是针对绝大多数文档的最佳选项，且在转换过程中不需要额外时间。 |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | 在这种情况下，转换器会尝试检测相邻背景图形元素的位置，并以适当方式纠正生成的 HTML。此选项可提升包含由多个相邻图形元素构成的背景的文档的导出结果（对于此类文档，PDF 渲染器，例如 Acrobat Reader，通常在渲染时尝试平滑元素的边界）。使用此选项，转换器会模仿 PDF 渲染器的行为。此选项可改善某些特定文档（使用此类复合背景）的导出布局，但会增加额外的处理时间（通常约为额外时间的 10-15%）。因此，在一般情况下不建议使用此模式。 |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

未使用特殊的抗锯齿处理。这是针对绝大多数文档的最佳选项，且在转换过程中不需要额外时间。

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

在这种情况下，转换器会尝试检测相邻背景图形元素的位置，并以适当方式纠正生成的 HTML。此选项可提升包含由多个相邻图形元素构成的背景的文档的导出结果（对于此类文档，PDF 渲染器，例如 Acrobat Reader，通常在渲染时尝试平滑元素的边界）。使用此选项，转换器会模仿 PDF 渲染器的行为。此选项可改善某些特定文档（使用此类复合背景）的导出布局，但会增加额外的处理时间（通常约为额外时间的 10-15%）。因此，在一般情况下不建议使用此模式。
