---
title: "Font.FontName"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Font プロパティ。Font オブジェクトのフォント名を取得します。"
type: docs
weight: 30
url: /ja/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

[`Font`](../) オブジェクトのフォント名を取得します。

```csharp
public string FontName { get; }
```

## 例

この例では、最初のページでテキストを検索し、最初のテキスト出現箇所のフォント名を表示する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォント名を表示
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


