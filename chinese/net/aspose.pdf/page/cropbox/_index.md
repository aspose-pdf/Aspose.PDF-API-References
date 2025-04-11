---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取或设置页面的裁剪框
type: docs
weight: 100
url: /zh/net/aspose.pdf/page/cropbox/
---
## Page.CropBox 属性

获取或设置页面的裁剪框。

```csharp
public Rectangle CropBox { get; set; }
```

## 示例

示例演示如何获取页面的裁剪框：

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### 另请参阅

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)