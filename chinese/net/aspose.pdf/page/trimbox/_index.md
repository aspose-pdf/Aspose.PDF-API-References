---
title: "Page.TrimBox"
second_title: "Aspose.PDF for .NET API 参考"
description: "Page 属性。获取或设置页面的裁剪框（trim box）。"
type: docs
weight: 290
url: /zh/net/aspose.pdf/page/trimbox/
---
## Page.TrimBox property

获取或设置页面的修剪框。

```csharp
public Rectangle TrimBox { get; set; }
```

## 示例

示例演示如何获取页面的裁剪框：

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### 另请参见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


