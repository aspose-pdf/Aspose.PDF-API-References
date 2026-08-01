---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragmentAbsorber プロパティ。検索結果のコレクションを取得します。このコレクションは TextFragment オブジェクトで構成されています。"
type: docs
weight: 90
url: /ja/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

検索結果のコレクションを取得します。このコレクションは [`TextFragment`](../../textfragment/) オブジェクトで構成されています。

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## 例

この例では、最初の PDF ドキュメントページでテキストを検索し、すべての検索結果を新しいテキストに置き換える方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// すべての検索結果のテキストを変更する
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


