---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "SVG 形式へのエクスポート用保存オプションです。"
type: docs
weight: 4720
url: /ja/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

SVG 形式へのエクスポート用保存オプションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | このフィールドには、変換中に作成された参照外部画像ファイル（埋め込み BMP や JPEG など）をカスタマイズして処理するために使用すべき保存戦略（存在する場合）を含めることができます。その戦略はリソースを処理し、生成された SVG 内で保存されたリソースの望ましい URI を表す文字列を返す必要があります。何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータ自身のコードで行う必要がある場合は、カスタムコードで 'CustomProcessingCancelled' フラグを 'imageSavingInfo' パラメータの変数に設定してください。これは、外部のカスタムコードがないかのように、リソースの処理に必要なすべての手順をコンバータ自身で実行することをコンバータに通知します。 |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | 出力が単一の zip アーカイブとして作成されるかどうかを指定します。マルチページのソースドキュメントのページごとの svg ファイルの命名規則（zip 化された出力ファイルセットにも適用されます）については、'TreatTargetFileNameAsDirectory' オプションのコメントを参照してください。 |
| [isScaleToPixels](#isScaleToPixels--) | 出力ドキュメントを組版ポイントからピクセルにスケーリングするかどうかを指定します。 |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | このオプションは、要求された出力ファイルと同名のターゲットディレクトリが（まだ存在しない場合に）作成されるかどうかを定義します。ディレクトリが作成される場合、ディレクトリにはページごとのすべての出力 SVG 画像が格納されます（以下で説明するように）。"いいえ" を選択した場合、最初のページ以外のページの出力ファイルは、メインの出力ファイルと同じディレクトリに正確に作成されますが、ファイル名に _[2...n] のサフィックスが付加され、ページ番号で定義されます。例えば、出力ファイルを "C:\\AsposeTests\\output.svg" と定義し、複数のページの svg ファイルが出力に含まれる場合、ページのファイルはディレクトリ "C:\\AsposeTests\\" にも作成され、名前は 'output.svg', 'output_2.svg', 'output_3.svg' などとなります。 |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | 出力が単一の zip アーカイブとして作成されるかどうかを指定します。マルチページのソースドキュメントのページごとの svg ファイルの命名規則（zip 化された出力ファイルセットにも適用されます）については、'TreatTargetFileNameAsDirectory' オプションのコメントを参照してください。 |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | このフィールドには、変換中に作成された参照外部画像ファイル（埋め込み BMP や JPEG など）をカスタマイズして処理するために使用すべき保存戦略（存在する場合）を含めることができます。 |
| [setScaleToPixels](#setScaleToPixels-boolean-) | 出力ドキュメントを組版ポイントからピクセルにスケーリングするかどうかを指定します。 |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | このオプションは、要求された出力ファイルと同名のターゲットディレクトリが（まだ存在しない場合に）作成されるかどうかを定義します。ディレクトリが作成される場合、ディレクトリにはページごとのすべての出力 SVG 画像が格納されます（以下で説明するように）。"いいえ" を選択した場合、最初のページ以外のページの出力ファイルは、メインの出力ファイルと同じディレクトリに正確に作成されますが、ファイル名に _[2...n] のサフィックスが付加され、ページ番号で定義されます。例えば、出力ファイルを "C:\\AsposeTests\\output.svg" と定義し、複数のページの svg ファイルが出力に含まれる場合、ページのファイルはディレクトリ "C:\\AsposeTests\\" にも作成され、名前は 'output.svg', 'output_2.svg', 'output_3.svg' などとなります。 |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

コンストラクタ

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

このフィールドには、変換中に作成された参照外部画像ファイル（埋め込み BMP や JPEG など）をカスタマイズして処理するために使用すべき保存戦略（存在する場合）を含めることができます。その戦略はリソースを処理し、生成された SVG 内で保存されたリソースの望ましい URI を表す文字列を返す必要があります。何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータ自身のコードで行う必要がある場合は、カスタムコードで 'CustomProcessingCancelled' フラグを 'imageSavingInfo' パラメータの変数に設定してください。これは、外部のカスタムコードがないかのように、リソースの処理に必要なすべての手順をコンバータ自身で実行することをコンバータに通知します。

**Returns:**
EmbeddedImagesSavingStrategy インスタンス

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

出力が単一の zip アーカイブとして作成されるかどうかを指定します。マルチページのソースドキュメントのページごとの svg ファイルの命名規則（zip 化された出力ファイルセットにも適用されます）については、'TreatTargetFileNameAsDirectory' オプションのコメントを参照してください。

**Returns:**
ブール値

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

出力ドキュメントを組版ポイントからピクセルにスケーリングするかどうかを指定します。

**Returns:**
ブール値

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

このオプションは、要求された出力ファイルと同名のターゲットディレクトリが（まだ存在しない場合に）作成されるかどうかを定義します。ディレクトリが作成される場合、ディレクトリにはページごとのすべての出力 SVG 画像が格納されます（以下で説明するように）。"いいえ" を選択した場合、最初のページ以外のページの出力ファイルは、メインの出力ファイルと同じディレクトリに正確に作成されますが、ファイル名に _[2...n] のサフィックスが付加され、ページ番号で定義されます。例えば、出力ファイルを "C:\\AsposeTests\\output.svg" と定義し、複数のページの svg ファイルが出力に含まれる場合、ページのファイルはディレクトリ "C:\\AsposeTests\\" にも作成され、名前は 'output.svg', 'output_2.svg', 'output_3.svg' などとなります。

**Returns:**
ブール値

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

出力が単一の zip アーカイブとして作成されるかどうかを指定します。マルチページのソースドキュメントのページごとの svg ファイルの命名規則（zip 化された出力ファイルセットにも適用されます）については、'TreatTargetFileNameAsDirectory' オプションのコメントを参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| compressOutputToZipArchive |  | ブール値 |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
このフィールドには、変換中に作成された参照外部画像ファイル（埋め込み BMP や JPEG など）をカスタマイズして処理するために使用すべき保存戦略（存在する場合）を含めることができます。

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

出力ドキュメントを組版ポイントからピクセルにスケーリングするかどうかを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleToPixels |  | ブール値 |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

このオプションは、要求された出力ファイルと同名のターゲットディレクトリが（まだ存在しない場合に）作成されるかどうかを定義します。ディレクトリが作成される場合、ディレクトリにはページごとのすべての出力 SVG 画像が格納されます（以下で説明するように）。"いいえ" を選択した場合、最初のページ以外のページの出力ファイルは、メインの出力ファイルと同じディレクトリに正確に作成されますが、ファイル名に _[2...n] のサフィックスが付加され、ページ番号で定義されます。例えば、出力ファイルを "C:\\AsposeTests\\output.svg" と定義し、複数のページの svg ファイルが出力に含まれる場合、ページのファイルはディレクトリ "C:\\AsposeTests\\" にも作成され、名前は 'output.svg', 'output_2.svg', 'output_3.svg' などとなります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | ブール値 |
