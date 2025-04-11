---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor プロパティ。抽出操作が実行されるページ範囲の終了ページを取得または設定します
type: docs
weight: 20
url: /ja/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage プロパティ

抽出操作が実行されるページ範囲の終了ページを取得または設定します。

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)