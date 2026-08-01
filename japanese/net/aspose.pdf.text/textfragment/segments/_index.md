---
title: "TextFragment.Segments"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragment プロパティ。現在の TextFragment のテキストセグメントを取得します。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

現在の `[`TextFragment`](../)` のテキストセグメントを取得します。

```csharp
public TextSegmentCollection Segments { get; set; }
```

## 備考

簡単に言うと、`[`TextSegment`](../../textsegment/)` オブジェクトは `[`TextFragment`](../)` オブジェクトの子です。上級ユーザーはセグメントに直接アクセスして、より複雑なテキスト編集シナリオを実行できます。詳細については、`[`TextFragment`](../)` オブジェクトの説明をご覧ください。

## 例

この例では、`[`TextFragment`](../)` 内のすべての `[`TextSegment`](../../textsegment/)` オブジェクトをナビゲートする方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// すべてのテキストセグメントをナビゲートし、そのテキストと配置情報を出力します。
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


