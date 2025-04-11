---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor プロパティ。テキスト抽出結果のモードを設定します
type: docs
weight: 40
url: /ja/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode プロパティ

テキスト抽出結果のモードを設定します。

```csharp
public int ExtractTextMode { get; set; }
```

### プロパティ値

0 は純粋なテキストモードで、1 は生の順序モードです。デフォルトは 0 です。

## 例

この例では、テキスト抽出シナリオにおける `ExtractTextMode` プロパティの使用法を示します。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)