---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentプロパティ。現在のTextFragmentのテキストセグメントを取得します
type: docs
weight: 120
url: /ja/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segmentsプロパティ

現在の[`TextFragment`](../)のテキストセグメントを取得します。

```csharp
public TextSegmentCollection Segments { get; set; }
```

## 備考

簡単に言うと、[`TextSegment`](../../textsegment/)オブジェクトは[`TextFragment`](../)オブジェクトの子です。高度なユーザーは、より複雑なテキスト編集シナリオを実行するためにセグメントに直接アクセスできます。詳細については、[`TextFragment`](../)オブジェクトの説明を参照してください。

## 例

この例では、[`TextFragment`](../)内のすべての[`TextSegment`](../../textsegment/)オブジェクトをナビゲートする方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [TextSegment](../../textsegment/)
* クラス [TextSegmentCollection](../../textsegmentcollection/)
* クラス [TextFragment](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)