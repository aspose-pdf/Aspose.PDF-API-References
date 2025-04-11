---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber プロパティ。テキスト抽出オプションを取得または設定します
type: docs
weight: 30
url: /ja/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions プロパティ

テキスト抽出オプションを取得または設定します。

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## 備考

抽出中にテキストフォーマットモード [`TextExtractionOptions`](../../textextractionoptions/) を定義することができます。デフォルトモードは Pure です。

## 例

この例では、Pure テキストフォーマットモードを設定し、テキスト抽出を実行する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### 関連項目

* クラス [TextExtractionOptions](../../textextractionoptions/)
* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)