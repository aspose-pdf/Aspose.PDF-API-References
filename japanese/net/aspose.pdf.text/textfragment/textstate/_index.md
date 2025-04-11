---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: TextFragment プロパティ。TextFragment オブジェクトが表すテキストのテキスト状態を取得または設定します
type: docs
weight: 150
url: /ja/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState プロパティ

[`TextFragment`](../) オブジェクトが表すテキストのテキスト状態を取得または設定します。

```csharp
public TextFragmentState TextState { get; }
```

## 備考

テキストの以下のプロパティを変更する方法を提供します: フォント フォントサイズ フォントスタイル 前景色 背景色

## 例

この例では、`TextState` オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [TextFragmentState](../../textfragmentstate/)
* クラス [TextFragment](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)