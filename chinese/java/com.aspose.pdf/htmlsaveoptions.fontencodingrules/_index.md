---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF for Java API 参考"
description: "此枚举定义了调优编码逻辑的规则"
type: docs
weight: 2050
url: /zh/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

此枚举定义了调优编码逻辑的规则

## 字段

| 字段 | 描述 |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode 是一种特殊机制，可帮助将输入代码解码为 Unicode 符号。根据规范，它必须作为获取特定输入代码的 Unicode 符号的首要机制使用。但某些文档使用非标准字体，要正确转换这些文档，可能需要降低 ToUnicode 的优先级并使用其他机制来解码输入代码。 |
| [Default](#Default) | 保持编码逻辑 "原样" - 符合 PDF 规范 |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode 是一种特殊机制，可帮助将输入代码解码为 Unicode 符号。根据规范，它必须作为获取特定输入代码的 Unicode 符号的首要机制使用。但某些文档使用非标准字体，要正确转换这些文档，可能需要降低 ToUnicode 的优先级并使用其他机制来解码输入代码。

### Default {#Default}
```
public static final byte Default
```

保持编码逻辑 "原样" - 符合 PDF 规范
