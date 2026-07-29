---
title: "Stamp.Pages"
second_title: "Aspose.PDF for .NET API 参考"
description: "Stamp 属性。获取或设置受印章影响的页码数组。如果 Pages 为 null，则文档的所有页都受影响"
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

获取或设置包含将受印章影响的页码的数组。如果 Pages = null，则文档的所有页都会受到影响。

```csharp
public int[] Pages { get; set; }
```

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//仅在第1、 第4 和第6 页上放置印章。
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参见

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


