---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragmentAbsorber プロパティ。検索結果の辞書を取得します。この辞書はキーに System.Text.RegularExpressions.Regex クラス、値に TextFragment を使用しています。"
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

検索結果の辞書を取得します。この辞書はキーに System.Text.RegularExpressions.Regex クラス、値に [`TextFragment`](../../textfragment/) を使用しています。

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## 例

この例は、最初の PDF document page で正規表現の配列を使用してテキストを検索する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// 正規表現を使用して、'h' で始まり 'o' で終わるすべての単語を検索する TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// 結果を取得
var results = absorber.RegexResults;
```

### 関連項目

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


