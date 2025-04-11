---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor メソッド。PDF ファイルから画像を抽出します
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage メソッド

PDF ファイルから画像を抽出します。

```csharp
public void ExtractImage()
```

## 例

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)