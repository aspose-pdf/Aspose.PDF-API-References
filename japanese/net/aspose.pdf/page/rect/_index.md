---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページの矩形を取得または設定します。取得する場合、指定されていればページのクロップボックスが返され、それ以外の場合はページのメディアボックスが返されます。設定する場合、ページのメディアボックスは常に設定されます。このプロパティはページの回転を考慮しないことに注意してください。回転を考慮したページの矩形を取得するには、ActualRectを使用してください。
type: docs
weight: 230
url: /ja/net/aspose.pdf/page/rect/
---
## Page.Rect プロパティ

ページの矩形を取得または設定します。取得する場合: 指定されていればページのクロップボックスが返され、それ以外の場合はページのメディアボックスが返されます。設定する場合: ページのメディアボックスは常に設定されます。このプロパティはページの回転を考慮しないことに注意してください。回転を考慮したページの矩形を取得するには、ActualRectを使用してください。

```csharp
public Rectangle Rect { get; set; }
```

## 例

例はページの矩形を取得する方法を示しています:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### 参照

* クラス [Rectangle](../../rectangle/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)