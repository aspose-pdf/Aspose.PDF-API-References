---
title: "PdfExtractor.HasNextImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor メソッド。PDF ドキュメントでさらに画像が取得可能か確認します。注意：このメソッドを使用する前に ExtractImage を呼び出す必要があります"
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

PDFドキュメントでさらに画像が取得可能か確認します。注: このメソッドを使用する前にExtractImageを呼び出す必要があります。

```csharp
public bool HasNextImage()
```

### 戻り値

さらに画像が取得可能な場合は true が返されます

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


