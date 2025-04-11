---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber プロパティ。検索オプションを取得または設定します。オプションは正規表現を使用した検索を可能にします。
type: docs
weight: 110
url: /ja/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions プロパティ

検索オプションを取得または設定します。オプションは正規表現を使用した検索を可能にします。

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## 例

この例では、正規表現を使用してテキストを検索する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 参照

* クラス [TextSearchOptions](../../textsearchoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)