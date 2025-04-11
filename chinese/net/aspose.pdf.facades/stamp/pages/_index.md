---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Stamp 属性。获取或设置将受到印章影响的页面编号数组。如果 Pages 为 null，则文档的所有页面都受到影响。
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages 属性

获取或设置将受到印章影响的页面编号数组。如果 Pages = null，则文档的所有页面都受到影响。

```csharp
public int[] Pages { get; set; }
```

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参阅

* 类 [Stamp](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)