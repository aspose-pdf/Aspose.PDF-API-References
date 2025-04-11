---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ToUnicodeProcessingRules 类。该类描述了可以用来解决 Adobe Preflight 错误“文本无法映射到 Unicode”的规则。
type: docs
weight: 11110
url: /zh/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules 类

该类描述了可以用来解决 Adobe Preflight 错误“文本无法映射到 Unicode”的规则。

```csharp
public class ToUnicodeProcessingRules
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | 初始化 `ToUnicodeProcessingRules` 类的新实例。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | 使用指定的选项初始化 `ToUnicodeProcessingRules` 类的新实例，以从 CMap 名称中删除空格。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | 使用指定的选项初始化 `ToUnicodeProcessingRules` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | 一些字体没有提供某些文本符号的 Unicode 信息。这种信息的缺失导致错误“文本无法映射到 Unicode”。使用此标志将非链接符号映射到 Unicode “空格”（代码 32）。 |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | 一些字体的 ToUnicode 字符代码映射中名称包含空格。这些空格可能导致 Unicode 文本映射错误。此标志命令从 ToUnicode 字符代码映射的名称中删除空格。默认值为 false。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)