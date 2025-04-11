---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: TextFragment プロパティ。TextFragment オブジェクトが表す String テキストオブジェクトを取得または設定します
type: docs
weight: 130
url: /ja/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text プロパティ

TextFragment オブジェクトが表す String テキストオブジェクトを取得または設定します。

```csharp
public string Text { get; set; }
```

## 例

この例では、テキストを検索し、TextFragment オブジェクトで表される最初の出現を置き換える方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [TextFragment](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)