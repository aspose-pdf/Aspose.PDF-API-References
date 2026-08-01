---
title: "TextFragmentAbsorber.Phrase"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragmentAbsorber プロパティ。PDF ドキュメントまたはページで TextFragmentAbsorber が検索するフレーズを取得または設定します。"
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

`[`TextFragmentAbsorber`](../)` が PDF ドキュメントまたはページで検索するフレーズを取得または設定します。

```csharp
public string Phrase { get; set; }
```

## 例

この例では、テキスト検索を複数回実行し、テキスト置換を行う方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// "hello" テキストのすべての出現箇所を見つけるために TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 別の単語を検索して置換します。
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


