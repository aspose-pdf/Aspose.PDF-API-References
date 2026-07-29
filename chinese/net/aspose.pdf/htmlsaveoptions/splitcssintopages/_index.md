---
title: "HtmlSaveOptions.SplitCssIntoPages"
second_title: "Aspose.PDF for .NET API 参考"
description: "HtmlSaveOptions 属性。当选择多页模式（即 SplitIntoPages 为 true）时，此属性定义是否为每个生成的 HTML 页面创建单独的 CSS 文件。默认情况下此属性为 false，所有页面共用一个大的公共 CSS。该模式下所有 CSS 的总大小（每页一个 CSS）通常远大于单个大 CSS 文件的大小，因为前者会在多个 CSS 文件中出现重复的 CSS 类。因此，仅在您需要对每个 HTML 页面独立进行后续处理，并且每个页面的 CSS 大小是最关键问题时，才建议使用此设置。"
type: docs
weight: 190
url: /zh/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

当选择多页模式（即 'SplitIntoPages' 为 true）时，此属性决定是否为每个生成的 HTML 页面创建单独的 CSS 文件。默认情况下此属性为 false，所有页面共用一个大的公共 CSS。以此模式生成的所有 CSS（每页一个 CSS）的总体大小通常远大于单个大 CSS 文件的大小，因为前者会在每个页面的多个 CSS 文件中出现重复的 CSS 类。因此，仅在您需要对每个 HTML 页面独立进行后续处理时才建议使用此设置，因为此时每个页面单独的 CSS 大小是最关键的问题。

```csharp
public bool SplitCssIntoPages { get; set; }
```

### 另请参见

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


