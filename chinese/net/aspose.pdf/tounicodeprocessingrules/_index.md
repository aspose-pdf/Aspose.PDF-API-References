---
title: "类 ToUnicodeProcessingRules"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.ToUnicodeProcessingRules 类。此类描述可用于解决 Adobe Preflight 错误 \"Text cannot be mapped to Unicode\"的规则"
type: docs
weight: 11300
url: /zh/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

此类描述可用于解决 Adobe Preflight 错误 "Text cannot be mapped to Unicode" 的规则。

```csharp
public class ToUnicodeProcessingRules
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | 初始化 `ToUnicodeProcessingRules` 类的新实例。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | 使用指定的选项来删除 CMap 名称中的空格，初始化 `ToUnicodeProcessingRules` 类的新实例。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | 使用指定的选项，初始化 `ToUnicodeProcessingRules` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | 某些字体未提供某些文本符号的 Unicode 信息。此信息缺失会导致错误 "Text cannot be mapped to Unicode"。使用此标志将未链接的符号映射为 Unicode "空格"(代码 32)。 |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | 某些字体的 ToUnicode 字符码映射名称中包含空格。这些空格可能导致 Unicode 文本映射错误。此标志用于从 ToUnicode 字符码映射的名称中删除空格。默认值为 false。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


