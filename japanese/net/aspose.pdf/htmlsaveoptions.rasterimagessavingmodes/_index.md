---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes 列挙型。変換された PDF にはラスタ画像が含まれることがあります （.png, .jpeg など）。この列挙型は、PDF を HTML に変換する際にラスタ画像をどのように処理するかの方法を定義します。
type: docs
weight: 5720
url: /ja/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes 列挙型

変換された PDF にはラスタ画像 (.png, *.jpeg など) が含まれることがあります。この列挙型は、PDF を HTML に変換する際にラスタ画像をどのように処理するかの方法を定義します。

```csharp
public enum RasterImagesSavingModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | 各異なるラスタファイルに対してラッパー SVG 画像が生成され、ラスタ画像はその SVG 画像に Base64 エンコードされた文字列として埋め込まれます。 |
| AsExternalPngFilesReferencedViaSvg | `1` | 異なるラスタ画像は PNG ファイルとして別々に配置されますが、ラッピング SVG 画像を通じて参照されます。つまり、各ラスタ画像に対して 1 つの PNG ファイルと 1 つの SVG が生成され、各 SVG には関連する PNG ファイルへのリンクが含まれます。 |
| AsEmbeddedPartsOfPngPageBackground | `2` | 各結果ページに対して 1 つの大きな PNG 背景ファイルが生成されます。ラスタ画像はそのファイルに埋め込まれ、その画像の領域としてレンダリングされます。各画像の外部 PNG ファイルは生成されず、変換結果のファイルセットにはページごとに 1 つの PNG ファイルのみが存在します。 |
| DontSave | `3` | 固定レイアウトの画像を保存しない。 |

### 参照

* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)