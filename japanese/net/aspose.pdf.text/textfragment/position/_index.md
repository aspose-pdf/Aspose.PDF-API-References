---
title: "TextFragment.Position"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragment プロパティ。TextFragment オブジェクトで表されるテキストの位置を取得または設定します。"
type: docs
weight: 90
url: /ja/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

`[`TextFragment`](../)` オブジェクトで表されるテキストの位置を取得または設定します。

```csharp
public Position Position { get; set; }
```

## 例

この例では、`[`TextFragment`](../)` オブジェクトで表されるテキストの配置を表示する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現のテキストと配置情報を表示します。
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


