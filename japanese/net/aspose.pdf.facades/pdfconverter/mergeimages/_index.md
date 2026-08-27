---
title: "PdfConverter.MergeImages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfConverter メソッド。画像ストリームのリストを 1 つの画像ストリームに結合します。サポートされていない形式の出力ストリームを使用する場合、デフォルトで JPEG にエンコードされますが、PNG/JPG/TIFF の出力形式もサポートされています。"
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

画像ストリームのリストを 1 つの画像ストリームに結合します。Png/jpg/tiff の出力形式がサポートされており、サポートされていない形式を使用した場合、出力ストリームはデフォルトで Jpeg としてエンコードされます。

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputImagesStreams | List`1 | 結合する画像ストリームのリストです。 |
| outputImageFormat | ImageFormat | 結合されたストリームの画像出力形式です。 |
| mergeMode | ImageMergeMode | マージモード。Png/Jpg 形式で使用されます。 |
| horizontal | Nullable`1 | 出力画像ストリームのキャンバス幅を設定する水平比率。ImageMergeMode.Center を使用した Png/Jpg 形式でのみ使用されます。 |
| vertical | Nullable`1 | 出力画像ストリームのキャンバス高さを設定する垂直比率。ImageMergeMode.Center を使用した Png/Jpg 形式でのみ使用されます。 |

### 戻り値

画像ストリームが出力画像形式でエンコードされます。

### 関連項目

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


