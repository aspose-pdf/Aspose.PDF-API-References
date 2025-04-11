---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber プロパティ。TextFragmentAbsorber が PDF ドキュメントまたはページで検索するフレーズを取得または設定します。
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase プロパティ

[`TextFragmentAbsorber`](../) が PDF ドキュメントまたはページで検索するフレーズを取得または設定します。

```csharp
public string Phrase { get; set; }
```

## 例

この例では、テキストを複数回検索し、テキストの置換を実行する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)