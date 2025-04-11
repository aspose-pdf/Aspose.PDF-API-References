---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontSavingModes 枚举。列举可以用于保存已保存 PDF 中引用的字体的模式
type: docs
weight: 5630
url: /zh/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes 枚举

列举可以用于保存已保存 PDF 中引用的字体的模式。

```csharp
public enum FontSavingModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | 所有引用的字体将被保存并作为 WOFF 字体引用。 |
| AlwaysSaveAsTTF | `1` | 所有引用的字体将被保存并作为 TTF 字体引用。 |
| AlwaysSaveAsEOT | `2` | 所有引用的字体将被保存并作为 EOT 字体引用。 |
| SaveInAllFormats | `3` | 所有引用的字体将被保存（并在 CSS 中引用）为 3 个独立文件：EOT、TTH、WOFF。这会增加输出数据的大小，但使输出适合绝大多数网页浏览器。 |
| DontSave | `4` | 所有引用的字体将不会被保存。 |

### 另请参阅

* 类 [HtmlSaveOptions](../htmlsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)