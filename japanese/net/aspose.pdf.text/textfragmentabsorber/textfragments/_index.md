---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber プロパティ。TextFragment オブジェクトで提示される検索の発生のコレクションを取得します
type: docs
weight: 90
url: /ja/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments プロパティ

[`TextFragment`](../../textfragment/) オブジェクトで提示される検索の発生のコレクションを取得します。

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## 例

この例では、最初の PDF ドキュメントページでテキストを見つけ、すべての検索の発生を新しいテキストに置き換える方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* クラス [TextFragmentCollection](../../textfragmentcollection/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)