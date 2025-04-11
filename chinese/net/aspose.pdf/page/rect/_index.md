---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Page 属性。获取或设置页面的矩形。如果指定，则返回页面裁剪框，否则返回页面媒体框。对于设置，页面媒体框始终设置。请注意，此属性不考虑页面旋转。要获取考虑旋转的页面矩形，请使用 ActualRect。
type: docs
weight: 230
url: /zh/net/aspose.pdf/page/rect/
---
## Page.Rect 属性

获取或设置页面的矩形。对于获取：如果指定，则返回页面裁剪框，否则返回页面媒体框。对于设置：页面媒体框始终设置。请注意，此属性不考虑页面旋转。要获取考虑旋转的页面矩形，请使用 ActualRect。

```csharp
public Rectangle Rect { get; set; }
```

## 示例

示例演示如何获取页面矩形：

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### 另请参阅

* 类 [Rectangle](../../rectangle/)
* 类 [Page](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)