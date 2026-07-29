---
title: "PdfAOptionsBase.ExcludeFontsStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfAOptionsBase 属性。获取或设置在 PDF/A 转换过程中删除字体以最小化输出文件大小的策略"
type: docs
weight: 30
url: /zh/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy property

获取或设置在 PDF/A 转换过程中删除字体以最小化输出文件大小的策略。

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value

删除字体的策略。该策略可以是 [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) 枚举中的一个值。默认是 SubsetFonts 和 RemoveDuplicatedFonts 的组合。

## 备注

此属性允许您控制转换过程中字体的处理方式。您可以选择删除重复字体、删除宽度不同的相似字体，或对字体进行子集化。

### 另请参见

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


