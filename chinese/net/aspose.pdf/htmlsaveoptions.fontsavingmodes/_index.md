---
title: HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API 参考
description: 枚举可用于保存保存的 PDF 中引用的字体 的模式
type: docs
weight: 3500
url: /zh/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes enumeration

枚举可用于保存保存的 PDF 中引用的字体 的模式

```csharp
public enum FontSavingModes
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | 所有引用的字体将被保存并引用为 WOFF-fonts |
| AlwaysSaveAsTTF | `1` | 所有引用的字体将被保存并引用为 TTF-fonts |
| AlwaysSaveAsEOT | `2` | 所有引用的字体将被保存并引用为 EOT-fonts |
| SaveInAllFormats | `3` | 所有引用的字体都将保存（并在 CSS 中引用）为 3 个独立的文件：EOT、TTH、WOFF. 它增加了输出数据的大小，但使输出适合绝大多数网络浏览器 |
| DontSave | `4` | 不会保存所有引用的字体。 |

### 也可以看看

* class [HtmlSaveOptions](../htmlsaveoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
