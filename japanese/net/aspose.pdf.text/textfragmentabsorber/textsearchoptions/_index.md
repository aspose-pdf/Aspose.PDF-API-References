---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragmentAbsorber プロパティ。検索オプションを取得または設定します。このオプションにより正規表現を使用した検索が可能になります。"
type: docs
weight: 110
url: /ja/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

検索オプションを取得または設定します。このオプションにより正規表現を使用した検索が可能になります。

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## 例

この例は、正規表現を使用してテキスト検索を実行する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// 正規表現を使用して、'h' で始まり 'o' で終わるすべての単語を検索するようにアブサーバーを設定します。
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// 「hello」単語を見つけて「Hi」に置き換える必要があります
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


