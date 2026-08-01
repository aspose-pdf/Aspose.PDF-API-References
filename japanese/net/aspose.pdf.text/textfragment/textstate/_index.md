---
title: "TextFragment.TextState"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragment プロパティ。TextFragment オブジェクトが表すテキストのテキスト状態を取得または設定します。"
type: docs
weight: 150
url: /ja/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

`[`TextFragment`](../)` オブジェクトが表すテキストのテキスト状態を取得または設定します。

```csharp
public TextFragmentState TextState { get; }
```

## 備考

テキストの次のプロパティを変更する方法を提供します：Font、FontSize、FontStyle、ForegroundColor、BackgroundColor。

## 例

この例では、`TextState` オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所の前景色を変更する
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// 最初のテキスト出現のフォントサイズを変更する
absorber.TextFragments[1].TextState.FontSize = 15;

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


