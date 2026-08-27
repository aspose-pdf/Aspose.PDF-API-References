---
title: "Page.Rect"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページの矩形を取得または設定します。取得時は、指定されている場合はページのトリムボックスが返され、指定がない場合はページのメディアボックスが返されます。設定時は常にページのメディアボックスを設定します。このプロパティはページの回転を考慮しません。回転を考慮したページ矩形を取得するには ActualRect を使用してください。"
type: docs
weight: 230
url: /ja/net/aspose.pdf/page/rect/
---
## Page.Rect property

ページの矩形を取得または設定します。取得時: 指定されていればページのクロップボックスが返され、そうでなければページのメディアボックスが返されます。設定時: 常にページのメディアボックスが設定されます。このプロパティはページの回転を考慮しないことに注意してください。回転を考慮したページ矩形を取得するには ActualRect を使用してください。

```csharp
public Rectangle Rect { get; set; }
```

## 例

例ではページ矩形の取得方法を示しています：

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


