---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase 属性。获取或设置在 PDF/A 转换过程中移除字体以最小化输出文件大小的策略
type: docs
weight: 30
url: /zh/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy 属性

获取或设置在 PDF/A 转换过程中移除字体以最小化输出文件大小的策略。

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### 属性值

移除字体的策略。这可以是 [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) 枚举中的一个值。默认值是 SubsetFonts 和 RemoveDuplicatedFonts 的组合。

## 备注

此属性允许您控制在转换过程中如何处理字体。您可以选择移除重复的字体、移除宽度不同的相似字体或子集字体。

### 另请参阅

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)