---
title: "Stamp.IsBackground"
second_title: "Aspose.PDF for .NET API 参考"
description: "Stamp 属性。获取或设置背景状态。如果为 true，印章将作为被印章页面的背景放置。默认设置为 false。"
type: docs
weight: 30
url: /zh/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

获取或设置背景状态。如果为 true，印章将放置在 spamped 页面 的背景中。默认设置为 false。

```csharp
public bool IsBackground { get; set; }
```

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参见

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


