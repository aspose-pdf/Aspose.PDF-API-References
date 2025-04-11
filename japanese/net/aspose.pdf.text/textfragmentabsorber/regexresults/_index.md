---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber プロパティ。System.Text.RegularExpressions.Regex クラスをキー、TextFragment を値とする検索の発生を辞書として取得します。
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults プロパティ

System.Text.RegularExpressions.Regex クラスをキー、[`TextFragment`](../../textfragment/) を値とする検索の発生を辞書として取得します。

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## 例

この例では、最初の PDF ドキュメントページで正規表現の配列を使用してテキストを見つける方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### 関連項目

* クラス [TextFragmentCollection](../../textfragmentcollection/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)