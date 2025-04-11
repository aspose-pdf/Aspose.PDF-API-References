---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter メソッド。画像ストリームのリストを1つの画像ストリームとしてマージします。サポートされていないフォーマットの出力ストリームを使用する場合、Png/jpg/tiff 出力フォーマットがサポートされており、デフォルトで Jpeg でエンコードされます。
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages メソッド

画像ストリームのリストを1つの画像ストリームとしてマージします。サポートされていないフォーマットの出力ストリームを使用する場合、Png/jpg/tiff 出力フォーマットがサポートされており、デフォルトで Jpeg でエンコードされます。

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputImagesStreams | List`1 | マージする画像ストリームのリスト。 |
| outputImageFormat | ImageFormat | マージされたストリームの画像出力フォーマット。 |
| mergeMode | ImageMergeMode | マージモード。Png/Jpg フォーマットに使用されます。 |
| horizontal | Nullable`1 | 出力画像ストリームのキャンバス幅を設定するための水平比率。ImageMergeMode.Center の Png/Jpg フォーマットでのみ使用されます。 |
| vertical | Nullable`1 | 出力画像ストリームのキャンバス高さを設定するための垂直比率。ImageMergeMode.Center の Png/Jpg フォーマットでのみ使用されます。 |

### 戻り値

出力画像フォーマットとしてエンコードされた画像ストリーム。

### 参照

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)