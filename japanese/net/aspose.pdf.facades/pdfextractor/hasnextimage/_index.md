---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor メソッド。PDF ドキュメントにアクセス可能な画像がさらにあるかどうかを確認します。注意 このメソッドを使用する前に ExtractImage を呼び出す必要があります。
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage メソッド

PDF ドキュメントにアクセス可能な画像がさらにあるかどうかを確認します。注意: このメソッドを使用する前に ExtractImage を呼び出す必要があります。

```csharp
public bool HasNextImage()
```

### 戻り値

アクセス可能な画像がさらにある場合は true

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