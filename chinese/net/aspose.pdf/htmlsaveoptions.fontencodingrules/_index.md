---
title: "枚举 HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlSaveOptionsFontEncodingRules 枚举。此枚举定义了用于调节编码逻辑的规则"
type: docs
weight: 5750
url: /zh/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

此枚举定义了用于调节编码逻辑的规则

```csharp
public enum FontEncodingRules : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 保持编码逻辑 "原样" - 符合 PDF 规范 |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode 是一种特殊机制，可帮助将输入代码解码为 Unicode 符号。根据规范，它必须作为首要机制用于获取特定输入代码的 Unicode 符号。但某些文档使用非标准字体，为了正确转换这些文档，可能需要降低 ToUnicode 的优先级并使用其他机制来解码输入代码。 |

### 另请参见

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


