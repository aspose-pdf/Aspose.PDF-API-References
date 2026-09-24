---
title: "HtmlSaveOptions.AdditionalMarginWidthInPoints"
linktitle: "AdditionalMarginWidthInPoints"
articleTitle: "AdditionalMarginWidthInPoints"
second_title: "Aspose.PDF for .NET"
description: "If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big..."
type: docs
weight: 190
url: "/net/aspose.pdf/htmlsaveoptions/additionalmarginwidthinpoints/"
product_version: "26.9.0"
---
## HtmlSaveOptions.AdditionalMarginWidthInPoints property

> **Deprecated.** AdditionalMarginWidthInPoints is deprecated, please use PageMarginIfAny instead.

If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont
 be not split into different HTML pages, but will be put into one big result HTML file.
 But each source PDF page will be represented with it's own 
 rectangle area in HTML (if necessary that areas can be bordered to show page paper edges
 with special attribute 'PageBorderIfAny'.
 This parameter defines width of margin that will be forcibly left around that output HTML-areas
 that represent pages of source PDF document.In essence it defines guaranteed interval between
 HTML-representations of PDF "paper" pages such mode of conversion.

```csharp
public int AdditionalMarginWidthInPoints { get; set; }
```

### Property Value

int

### See Also

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

