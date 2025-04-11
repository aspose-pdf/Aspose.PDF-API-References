---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: フォントプロパティ。Fontオブジェクトのフォント名を取得します
type: docs
weight: 30
url: /ja/net/aspose.pdf.text/font/fontname/
---
## Font.FontName プロパティ

[`Font`](../) オブジェクトのフォント名を取得します。

```csharp
public string FontName { get; }
```

## 例

この例では、最初のページでテキストを検索し、最初のテキスト出現のフォント名を表示する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [Font](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)