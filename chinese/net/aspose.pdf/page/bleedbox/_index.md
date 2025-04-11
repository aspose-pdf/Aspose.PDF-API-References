---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取或设置页面的出血框
type: docs
weight: 70
url: /zh/net/aspose.pdf/page/bleedbox/
---
## Page.BleedBox 属性

获取或设置页面的出血框。

```csharp
public Rectangle BleedBox { get; set; }
```

## 示例

示例演示如何获取页面的出血框：

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### 另请参阅

* 类 [Rectangle](../../rectangle/)
* 类 [Page](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)