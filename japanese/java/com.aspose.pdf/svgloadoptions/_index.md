---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF 文書に SVG ファイルをロード/インポートするためのオプションを表します。"
type: docs
weight: 4700
url: /ja/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

PDF 文書に SVG ファイルをロード/インポートするためのオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | {@code SvgLoadOptions} オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | 変換中に使用される変換エンジンを選択できるようにします。現在、新しいエンジンは B テスト段階にあり、デフォルトではこの値は ConversionEngines.LegacyEngine に設定されています。 |
| [getPageInfo](#getPageInfo--) | ドキュメントの読み込み時に適用されるページ情報を取得します。 |
| [isAdjustPageSize](#isAdjustPageSize--) | PDF ページサイズを SVG サイズに合わせます |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | PDF ページサイズを SVG サイズに合わせます |
| [setConversionEngine](#setConversionEngine-int-) | 変換中に使用される変換エンジンを選択できるようにします。現在、新しいエンジンは B テスト段階にあり、デフォルトではこの値は ConversionEngines.LegacyEngine に設定されています。 |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | ドキュメントの読み込み時に適用されるページ情報を設定します。 |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

{@code SvgLoadOptions} オブジェクトを作成します。

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

変換中に使用される変換エンジンを選択できるようにします。現在、新しいエンジンは B テスト段階にあり、デフォルトではこの値は ConversionEngines.LegacyEngine に設定されています。

**Returns:**
ConversionEngines 要素 @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

ドキュメントの読み込み時に適用されるページ情報を取得します。

**Returns:**
PageInfo オブジェクト

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

PDF ページサイズを SVG サイズに合わせます

**Returns:**
ブール値

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

PDF ページサイズを SVG サイズに合わせます

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

変換中に使用される変換エンジンを選択できるようにします。現在、新しいエンジンは B テスト段階にあり、デフォルトではこの値は ConversionEngines.LegacyEngine に設定されています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines 要素 @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
ドキュメントの読み込み時に適用されるページ情報を設定します。
