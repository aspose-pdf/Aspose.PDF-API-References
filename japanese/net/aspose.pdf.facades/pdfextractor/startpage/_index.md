---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor プロパティ。抽出操作が実行されるページ範囲の開始ページを取得または設定します。
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage プロパティ

抽出操作が実行されるページ範囲の開始ページを取得または設定します。

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)