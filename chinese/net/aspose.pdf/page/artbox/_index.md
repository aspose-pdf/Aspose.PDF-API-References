---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取或设置页面的艺术框
type: docs
weight: 30
url: /zh/net/aspose.pdf/page/artbox/
---
## Page.ArtBox 属性

获取或设置页面的艺术框。

```csharp
public Rectangle ArtBox { get; set; }
```

## 示例

示例演示如何获取页面的艺术框：

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### 另请参阅

* 类 [Rectangle](../../rectangle/)
* 类 [Page](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)