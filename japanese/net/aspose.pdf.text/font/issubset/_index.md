---
title: "Font.IsSubset"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Font プロパティ。フォントがサブセットであるかどうかを示す値を取得または設定します。IFont に基づく Font は自動的にサブセット化され、埋め込まれます。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

フォントがサブセットであるかどうかを示す値を取得または設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。

```csharp
public bool IsSubset { get; set; }
```

## 例

この例は、最初のページでテキストを検索し、フォントがサブセットであるかどうかを示す値を取得する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントの IsSubset 値を表示します
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


