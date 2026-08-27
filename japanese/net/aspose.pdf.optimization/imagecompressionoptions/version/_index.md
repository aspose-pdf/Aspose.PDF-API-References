---
title: "ImageCompressionOptions.Version"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ImageCompressionOptions プロパティ。 圧縮アルゴリズムのバージョンです。 可能な値は 1. 標準圧縮、2. 高速改良圧縮（標準より速いが、すべての画像に適用できるわけではない）、3. 混合圧縮（高速アルゴリズムで圧縮できない画像に標準圧縮を適用し、最高の圧縮率を得られるが、速度は高速アルゴリズムより遅くなる）。 バージョン Fast は画像のリサイズには適用できず、標準手法が使用されます。 デフォルトは Standard です。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## ImageCompressionOptions.Version property

圧縮アルゴリズムのバージョン。可能な値は次のとおりです：1. standard compression、2. fast（標準より高速な改良圧縮ですが、すべての画像に適用できるわけではありません）、3. mixed（高速アルゴリズムで圧縮できない画像に標準圧縮が適用されます。これにより最高の圧縮が得られる可能性がありますが、"fast" アルゴリズムより遅くなります。バージョン "Fast" は画像のリサイズには適用できず（標準手法が使用されます）。デフォルトは "Standard" です。

```csharp
public ImageCompressionVersion Version { get; set; }
```

### 関連項目

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)


