---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase 属性。获取或设置一个值，指示在 PDF/A 转换过程中是否需要额外的手段来保持文本对齐。
type: docs
weight: 10
url: /zh/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText 属性

获取或设置一个值，指示在 PDF/A 转换过程中是否需要额外的手段来保持文本对齐。

```csharp
public bool AlignText { get; set; }
```

### 属性值

如果文本对齐发生变化并且需要额外的操作来恢复，则为 `true`；否则为 `false`。

## 备注

当设置为 `true` 时，转换过程将尝试恢复原始文本段边界。对于大多数文档，通常不需要将此属性从默认的 `false` 值更改，因为在默认转换过程中文本对齐不会发生变化。

### 另请参阅

* 类 [PdfAOptionsBase](../)
* 命名空间 [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../../)