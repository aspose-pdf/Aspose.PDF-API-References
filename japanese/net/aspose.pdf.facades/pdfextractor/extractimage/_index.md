---
title: "PdfExtractor.ExtractImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor メソッド。PDF ファイルから画像を抽出します。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

PDFファイルから画像を抽出します。

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


