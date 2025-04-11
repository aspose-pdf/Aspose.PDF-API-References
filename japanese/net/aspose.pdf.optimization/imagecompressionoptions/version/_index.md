---
title: ImageCompressionOptions.Version
second_title: Aspose.PDF for .NET API Reference
description: ImageCompressionOptions プロパティ。圧縮アルゴリズムのバージョン。可能な値は 1. 標準圧縮 2. 高速（標準よりも速い改善された圧縮ですが、すべての画像に適用できるわけではありません） 3. 混合（高速アルゴリズムで圧縮できない画像に標準圧縮が適用され、これにより最良の圧縮が得られる可能性がありますが、高速アルゴリズムよりも遅くなります）。バージョン「Fast」は画像のリサイズには適用できません（標準メソッドが使用されます）。デフォルトは「Standard」です。
type: docs
weight: 70
url: /ja/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## ImageCompressionOptions.Version プロパティ

圧縮アルゴリズムのバージョン。可能な値は：1. 標準圧縮、2. 高速（標準よりも速い改善された圧縮ですが、すべての画像に適用できるわけではありません）、3. 混合（高速アルゴリズムで圧縮できない画像に標準圧縮が適用され、これにより最良の圧縮が得られる可能性がありますが、「高速」アルゴリズムよりも遅くなります）。バージョン「Fast」は画像のリサイズには適用できません（標準メソッドが使用されます）。デフォルトは「Standard」です。

```csharp
public ImageCompressionVersion Version { get; set; }
```

### 参照

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)