---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions 属性。当选择多页面模式，即 SplitIntoPages 为 true 时，此属性定义是否应为每个结果 HTML 页面创建单独的 CSS 文件。默认情况下，此属性为 false，因此将为所有创建的页面创建一个大的公共 CSS。以这种模式生成的所有 CSS 的总大小（每页一个 CSS）通常远大于一个大 CSS 文件的大小，因为在前一种情况下，CSS 类在每个页面的多个 CSS 文件中是重复的。因此，只有在您对将来独立处理每个 HTML 页面感兴趣时，才应使用此设置，因此每个页面单独的 CSS 大小是最关键的问题。
type: docs
weight: 190
url: /zh/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages 属性

当选择多页面模式（即 'SplitIntoPages' 为 'true'）时，此属性定义是否应为每个结果 HTML 页面创建单独的 CSS 文件。默认情况下，此属性为 false，因此将为所有创建的页面创建一个大的公共 CSS。以这种模式生成的所有 CSS 的总大小（每页一个 CSS）通常远大于一个大 CSS 文件的大小，因为在前一种情况下，CSS 类在每个页面的多个 CSS 文件中是重复的。因此，只有在您对将来独立处理每个 HTML 页面感兴趣时，才应使用此设置，因此每个页面单独的 CSS 大小是最关键的问题。

```csharp
public bool SplitCssIntoPages { get; set; }
```

### 另请参阅

* 类 [HtmlSaveOptions](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)