---
title: "PdfExtractor.StartPage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor プロパティ。抽出操作が実行されるページ範囲内の開始ページを取得または設定します。"
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

抽出操作が実行されるページ範囲内の開始ページを取得または設定します。

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


