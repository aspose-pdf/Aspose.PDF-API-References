---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "変換されたPDFにはラスタ画像（.png、.jpeg など）が含まれることがあります。この列挙体は、PDFからHTMLへの変換中にラスタ画像をどのように処理できるかの方法を定義します"
type: docs
weight: 2140
url: /ja/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

変換されたPDFにはラスタ画像（.png、.jpeg など）が含まれることがあります。この列挙体は、PDFからHTMLへの変換中にラスタ画像をどのように処理できるかの方法を定義します

## フィールド

| フィールド | 説明 |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | 各結果ページごとに大きな PNG 背景ファイルが生成されます。ラスタ画像はそのファイルに埋め込まれ、画像の領域として描画されます。各画像ごとの外部 PNG ファイルは生成されず、ページごとに 1 つの PNG ファイルのみが変換結果のファイルセットに含まれます。 |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | 個別のラスタ画像は PNG ファイルとして分離されますが、ラップする SVG 画像を介して参照されます。つまり、各ラスタ画像ごとに 1 つの PNG ファイルと 1 つの SVG が生成され、各 SVG には該当する PNG ファイルへのリンクが含まれます。 |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | 各個別のラスタファイルごとにラッパー SVG 画像が生成され、ラスタ画像は Base64 エンコードされた文字列としてその SVG 画像に埋め込まれます。 |
| [DontSave](#DontSave) | 固定レイアウト用に画像を保存しないでください。 |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

各結果ページごとに大きな PNG 背景ファイルが生成されます。ラスタ画像はそのファイルに埋め込まれ、画像の領域として描画されます。各画像ごとの外部 PNG ファイルは生成されず、ページごとに 1 つの PNG ファイルのみが変換結果のファイルセットに含まれます。

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

個別のラスタ画像は PNG ファイルとして分離されますが、ラップする SVG 画像を介して参照されます。つまり、各ラスタ画像ごとに 1 つの PNG ファイルと 1 つの SVG が生成され、各 SVG には該当する PNG ファイルへのリンクが含まれます。

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

各個別のラスタファイルごとにラッパー SVG 画像が生成され、ラスタ画像は Base64 エンコードされた文字列としてその SVG 画像に埋め込まれます。

### DontSave {#DontSave}
```
public static final int DontSave
```

固定レイアウト用に画像を保存しないでください。
