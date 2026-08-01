---
title: "PdfExtractor.EndPage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor プロパティ。抽出操作が実行されるページ範囲の終了ページを取得または設定します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


