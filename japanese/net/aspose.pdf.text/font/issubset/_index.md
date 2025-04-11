---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: フォントプロパティ。フォントがサブセットであるかどうかを示す値を取得または設定します。IFontに基づくフォントは自動的にサブセット化され、埋め込まれます
type: docs
weight: 70
url: /ja/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset プロパティ

フォントがサブセットであるかどうかを示す値を取得または設定します。IFontに基づくフォントは自動的にサブセット化され、埋め込まれます

```csharp
public bool IsSubset { get; set; }
```

## 例

この例では、最初のページでテキストを検索し、フォントがサブセットであるかどうかを示す値を取得する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [Font](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)