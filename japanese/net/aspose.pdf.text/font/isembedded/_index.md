---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: フォントプロパティ。フォントが埋め込まれているかどうかを示す値を取得または設定します。IFontに基づくフォントは自動的にサブセット化され、埋め込まれます
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded プロパティ

フォントが埋め込まれているかどうかを示す値を取得または設定します。IFontに基づくフォントは自動的にサブセット化され、埋め込まれます

```csharp
public bool IsEmbedded { get; set; }
```

## 例

次の例は、フォントを見つけて埋め込まれているとしてマークし、ドキュメントのページ上のテキストを検索してテキストフォントを置き換える方法を示しています。

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [FontRepository](../../fontrepository/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [Font](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)