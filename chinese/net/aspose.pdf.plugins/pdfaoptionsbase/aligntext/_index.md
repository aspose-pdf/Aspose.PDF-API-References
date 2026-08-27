---
title: "PdfAOptionsBase.AlignText"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfAOptionsBase 属性。获取或设置一个值，指示在 PDF/A 转换过程中是否需要额外手段来保持文本对齐"
type: docs
weight: 10
url: /zh/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

获取或设置一个值，指示在 PDF/A 转换过程中是否需要额外的手段来保持文本对齐。

```csharp
public bool AlignText { get; set; }
```

### Property Value

`true` 表示文本对齐已更改且需要额外操作来恢复；否则为 `false`。

## 备注

当设置为 `true` 时，转换过程将尝试恢复原始文本段的边界。对于大多数文档，无需将此属性从默认的 `false` 值更改，因为在默认转换过程中文本对齐不会改变。

### 另请参见

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


