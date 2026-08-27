---
title: "PdfExtractor.ExtractTextMode"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor プロパティ。テキスト抽出結果のモードを設定します。"
type: docs
weight: 40
url: /ja/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

テキスト抽出結果のモードを設定します。

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 は純粋テキストモード、1 は生の順序モードです。デフォルトは 0 です。

## 例

この例では、テキスト抽出シナリオにおける `ExtractTextMode` プロパティの使用方法を示します。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


