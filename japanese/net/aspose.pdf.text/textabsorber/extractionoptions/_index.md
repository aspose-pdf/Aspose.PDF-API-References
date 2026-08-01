---
title: "TextAbsorber.ExtractionOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextAbsorber プロパティ。テキスト抽出オプションを取得または設定します。"
type: docs
weight: 30
url: /ja/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

テキスト抽出オプションを取得または設定します。

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## 備考

抽出中にテキスト書式設定モードを [`TextExtractionOptions`](../../textextractionoptions/) で定義できます。デフォルトのモードは Pure です。

## 例

この例は Pure テキスト書式設定モードを設定し、テキスト抽出を実行する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// 書式設定付きでテキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber();

// Pure テキスト書式設定モードを設定します。
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// すべての document のページに対してアブソーバーを受け入れます
doc.Pages.Accept(absorber);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;
```

### 関連項目

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


