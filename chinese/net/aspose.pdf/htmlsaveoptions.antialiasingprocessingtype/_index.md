---
title: HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API 参考
description: 这个枚举描述了转换过程中可能的抗锯齿措施
type: docs
weight: 3440
url: /zh/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

这个枚举描述了转换过程中可能的抗锯齿措施

```csharp
public enum AntialiasingProcessingType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | 没有使用特殊的抗锯齿处理。这是压倒大多数文档的最佳选项 ，并且在转换期间不需要额外的时间 |
| TryCorrectResultHtml | `1` | 在这种情况下，转换器尝试检测具有相邻背景图形 元素的位置，并以相关方式纠正结果 HTML。 此选项允许增强导出包含从几个相邻图形元素构建的 backgrounds 的文档的结果（对于此类文档 PDF 渲染器, fe Acrobat Reader, 通常在渲染过程中尝试平滑元素的边界。 使用此选项转换器会模仿 PDF 渲染器的行为。 此选项允许增强某些特定文档（使用此类复合背景）的导出结果布局， 但它需要额外的处理时间（通常约为额外时间的 10-15%）。 所以一般情况下不建议使用此模式。 |

### 也可以看看

* class [HtmlSaveOptions](../htmlsaveoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
