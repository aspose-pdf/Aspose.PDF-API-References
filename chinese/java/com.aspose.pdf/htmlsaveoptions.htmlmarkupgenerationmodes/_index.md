---
title: "HtmlSaveOptions.HtmlMarkupGenerationModes"
linktitle: "HtmlSaveOptions.HtmlMarkupGenerationModes"
second_title: "Aspose.PDF for Java API 参考"
description: "有时会出现对生成 HTML 的特定需求。此枚举定义了在 PDF 转换为 HTML 过程中可用于满足此类特定需求的 HTML 生成模式。"
type: docs
weight: 2090
url: /zh/java/com.aspose.pdf/htmlsaveoptions.htmlmarkupgenerationmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlMarkupGenerationModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes

```
public static final class HtmlSaveOptions.HtmlMarkupGenerationModes extends com.aspose.ms.System.Enum
```

有时会出现对生成的 HTML 的特定需求。此枚举定义了在 PDF 转换为 HTML 期间可用于满足此类特定需求的 HTML 准备模式。

## 字段

| 字段 | 描述 |
| --- | --- |
| [WriteAllHtml](#WriteAllHtml) | 默认模式在不存在任何特定需求时使用。生成的输出将包含 HTML 的所有部分，且不进行任何特殊的额外处理。 |
| [WriteOnlyBodyContent](#WriteOnlyBodyContent) | 将剥除所有位于 HTML body 之外的 HTML 内容，即仅保留位于 {@code } 标签内部的内容。 |

### WriteAllHtml {#WriteAllHtml}
```
public static final int WriteAllHtml
```

默认模式在不存在任何特定需求时使用。生成的输出将包含 HTML 的所有部分，且不进行任何特殊的额外处理。

### WriteOnlyBodyContent {#WriteOnlyBodyContent}
```
public static final int WriteOnlyBodyContent
```

将剥除所有位于 HTML body 之外的 HTML 内容，即仅保留位于 {@code } 标签内部的内容。
