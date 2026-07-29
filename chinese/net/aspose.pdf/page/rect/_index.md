---
title: "Page.Rect"
second_title: "Aspose.PDF for .NET API 参考"
description: "Page 属性。获取或设置页面的矩形。获取时，如果指定则返回页面裁剪框，否则返回页面媒体框。设置时始终设置页面媒体框。请注意，此属性不考虑页面旋转。若要获取考虑旋转后的页面矩形，请使用 ActualRect。"
type: docs
weight: 230
url: /zh/net/aspose.pdf/page/rect/
---
## Page.Rect property

获取或设置页面的矩形。获取时：如果指定，则返回页面裁剪框，否则返回页面媒体框。设置时：始终设置页面媒体框。请注意，此属性不考虑页面旋转。若要获取考虑旋转的页面矩形，请使用 ActualRect。

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

### 另请参见

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


