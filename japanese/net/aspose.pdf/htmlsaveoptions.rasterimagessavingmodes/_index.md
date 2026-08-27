---
title: "列挙型 HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes 列挙型。変換された PDF にはラスタ画像（.png、.jpeg など）を含めることができます。この列挙型は、PDF から HTML への変換中にラスタ画像をどのように処理するかの方法を定義します。"
type: docs
weight: 5850
url: /ja/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

変換された PDF にはラスタ画像（.png、*.jpeg など）を含めることができます。この列挙型は、PDF から HTML への変換中にラスタ画像をどのように処理するかの方法を定義します。

```csharp
public enum RasterImagesSavingModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | 各個別のラスタファイルごとにラップ用 SVG 画像が生成され、ラスタ画像は Base64 エンコードされた文字列としてその SVG 画像に埋め込まれます。 |
| AsExternalPngFilesReferencedViaSvg | `1` | 個別のラスタ画像は PNG ファイルとして分離されますが、ラップ用 SVG 画像を介して参照されます。つまり、各ラスタ画像につき 1 つの PNG ファイルと 1 つの SVG が生成され、各 SVG には該当する PNG ファイルへのリンクが含まれます。 |
| AsEmbeddedPartsOfPngPageBackground | `2` | 各結果ページごとに大きな PNG 背景ファイルが生成されます。ラスタ画像はそのファイルに埋め込まれ、画像の領域として描画されます。各画像ごとの外部 PNG ファイルは生成されず、ページごとに 1 つの PNG ファイルのみが変換結果のファイルセットに含まれます。 |
| DontSave | `3` | Fixed Layout 用に画像を保存しないでください |

### 関連項目

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


