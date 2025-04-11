---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取或设置页面的媒体框
type: docs
weight: 180
url: /zh/net/aspose.pdf/page/mediabox/
---
## Page.MediaBox 属性

获取或设置页面的媒体框。

```csharp
public Rectangle MediaBox { get; set; }
```

## 示例

示例演示如何获取页面的媒体框：

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### 另请参阅

* 类 [Rectangle](../../rectangle/)
* 类 [Page](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)