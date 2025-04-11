---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取或设置页面的裁剪框
type: docs
weight: 290
url: /zh/net/aspose.pdf/page/trimbox/
---
## Page.TrimBox 属性

获取或设置页面的裁剪框。

```csharp
public Rectangle TrimBox { get; set; }
```

## 示例

示例演示如何获取页面的裁剪框：

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### 另请参阅

* 类 [Rectangle](../../rectangle/)
* 类 [Page](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)