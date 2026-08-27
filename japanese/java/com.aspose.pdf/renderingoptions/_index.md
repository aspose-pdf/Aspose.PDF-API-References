---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "レンダリングオプションを表します"
type: docs
weight: 4150
url: /ja/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

レンダリングオプションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | 新しい {@code RenderingOptions} オブジェクトのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは以下の手順に従います：1. ユーザーが明示的に DefaultFontName プロパティを設定している場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、{@code FontRepository.Sources} を通じて追加されたフォントを検索します。3. テキストを解析してアルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステム内で検索します。 |
| [getBarcodeOptimization](#getBarcodeOptimization--) | バーコード最適化モードを取得します。 |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | すべてのフォントを TTF Unicode バージョンに変換することを示します。これは互換性の理由やフォント使用量の最適化に有用です。新しい TTF フォントは元のフォントのすべてのシンボルを持つのではなく、テキストで使用されているシンボルのみを含むためです。 |
| [getDefaultFontName](#getDefaultFontName--) | 欠落したフォントの代替に使用されるフォントのデフォルト名を取得/設定します。 |
| [getHeightExtraUnits](#getHeightExtraUnits--) | AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。 |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。 |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | 補間の高品質モードを取得または設定します。 |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | フォントキャッシュ内のフォントの最大数です。デフォルト値は 10 です。 |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | シンボルキャッシュ内のシンボルの最大数です。デフォルト値は 100 です。 |
| [getOptimizeDimensions](#getOptimizeDimensions--) | 次元最適化モードを取得または設定します。 |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | ページ上のすべての画像をページ幅に合わせて拡大縮小するために使用される値を取得または設定します。 |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | システムフォントがネイティブにレンダリングされるモードを取得します。 |
| [getUseFontHinting](#getUseFontHinting--) | このフラグを使用するとフォントヒンティング機構が有効になります。フォントヒンティングとは、アウトラインフォントの表示を調整するための数学的指示を使用することです。場合によっては、このフラグをオンにすることでテキストの可読性に関する問題が解決することがあります。現在のところ、このフラグの使用は TTF フォントに対してのみ効果があり、これらのフォントがソース文書で使用されている場合に適用されます。 |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | 新しいイメージングエンジンが使用されるかどうかを決定するフラグを取得します。 |
| [getWidthExtraUnits](#getWidthExtraUnits--) | AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。 |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | PDF ファイルの処理中にエラーをスキップするために使用される値を取得します。 |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは以下の手順に従います：1. ユーザーが明示的に DefaultFontName プロパティを設定している場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、{@code FontRepository.Sources} を通じて追加されたフォントを検索します。3. テキストを解析してアルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステム内で検索します。 |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | バーコード最適化モードを設定します。 |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | すべてのフォントを TTF Unicode バージョンに変換することを示します。これは互換性の理由やフォント使用量の最適化に有用です。新しい TTF フォントは元のフォントのすべてのシンボルを持つのではなく、テキストで使用されているシンボルのみを含むためです。 |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | 欠落したフォントの代替に使用されるフォントのデフォルト名を取得/設定します。 |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。 |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。 |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | 補間の高品質モードを取得または設定します。 |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | フォントキャッシュ内のフォントの最大数です。デフォルト値は 10 です。 |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | シンボルキャッシュ内のシンボルの最大数です。デフォルト値は 100 です。 |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | 次元最適化モードを取得または設定します。 |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | ページ上のすべての画像をページ幅に合わせて拡大縮小するために使用される値を取得または設定します。 |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | システムフォントがネイティブにレンダリングされるモードを設定します。 |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | PDF ファイルの処理中にエラーをスキップするために使用される値を設定します。 |
| [setUseFontHinting](#setUseFontHinting-boolean-) | このフラグを使用するとフォントヒンティング機構が有効になります。フォントヒンティングとは、アウトラインフォントの表示を調整するための数学的指示を使用することです。場合によっては、このフラグをオンにすることでテキストの可読性に関する問題が解決することがあります。現在のところ、このフラグの使用は TTF フォントに対してのみ効果があり、これらのフォントがソース文書で使用されている場合に適用されます。 |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | 新しいイメージングエンジンが使用されるかどうかを決定するフラグを設定します。 |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。 |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

新しい {@code RenderingOptions} オブジェクトのインスタンスを初期化します。

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは以下の手順に従います：1. ユーザーが明示的に DefaultFontName プロパティを設定している場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、{@code FontRepository.Sources} を通じて追加されたフォントを検索します。3. テキストを解析してアルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステム内で検索します。

**Returns:**
ブール値

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

バーコード最適化モードを取得します。

**Returns:**
ブール値

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

すべてのフォントを TTF Unicode バージョンに変換することを示します。これは互換性の理由やフォント使用量の最適化に有用です。新しい TTF フォントは元のフォントのすべてのシンボルを持つのではなく、テキストで使用されているシンボルのみを含むためです。

**Returns:**
ブール値

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

欠落したフォントの代替に使用されるフォントのデフォルト名を取得/設定します。

**Returns:**
文字列値

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。

**Returns:**
float 値

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。

**Returns:**
ブール値

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

補間の高品質モードを取得または設定します。

**Returns:**
ブール値

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

フォントキャッシュ内のフォントの最大数です。デフォルト値は 10 です。

**Returns:**
int 値です。

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

シンボルキャッシュ内のシンボルの最大数です。デフォルト値は 100 です。

**Returns:**
int 値です。

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

次元最適化モードを取得または設定します。

**Returns:**
ブール値

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

ページ上のすべての画像をページ幅に合わせて拡大縮小するために使用される値を取得または設定します。

**Returns:**
boolean 値 @deprecated ScaleImagesToFitPageWidth は非推奨です。

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

システムフォントがネイティブにレンダリングされるモードを取得します。

**Returns:**
ブール値

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

このフラグを使用するとフォントヒンティング機構が有効になります。フォントヒンティングとは、アウトラインフォントの表示を調整するための数学的指示を使用することです。場合によっては、このフラグをオンにすることでテキストの可読性に関する問題が解決することがあります。現在のところ、このフラグの使用は TTF フォントに対してのみ効果があり、これらのフォントがソース文書で使用されている場合に適用されます。

**Returns:**
ブール値

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

新しいイメージングエンジンが使用されるかどうかを決定するフラグを取得します。

**Returns:**
boolean 値 @deprecated UseNewImagingEngine は非推奨です

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。

**Returns:**
float 値

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

PDF ファイルの処理中にエラーをスキップするために使用される値を取得します。

**Returns:**
ブール値

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは以下の手順に従います：1. ユーザーが明示的に DefaultFontName プロパティを設定している場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、{@code FontRepository.Sources} を通じて追加されたフォントを検索します。3. テキストを解析してアルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステム内で検索します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

バーコード最適化モードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

すべてのフォントを TTF Unicode バージョンに変換することを示します。これは互換性の理由やフォント使用量の最適化に有用です。新しい TTF フォントは元のフォントのすべてのシンボルを持つのではなく、テキストで使用されているシンボルのみを含むためです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
欠落したフォントの代替に使用されるフォントのデフォルト名を取得/設定します。

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

補間の高品質モードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

フォントキャッシュ内のフォントの最大数です。デフォルト値は 10 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

シンボルキャッシュ内のシンボルの最大数です。デフォルト値は 100 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

次元最適化モードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

ページ上のすべての画像をページ幅に合わせて拡大縮小するために使用される値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値 @deprecated ScaleImagesToFitPageWidth は非推奨です。 |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

システムフォントがネイティブにレンダリングされるモードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

PDF ファイルの処理中にエラーをスキップするために使用される値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

このフラグを使用するとフォントヒンティング機構が有効になります。フォントヒンティングとは、アウトラインフォントの表示を調整するための数学的指示を使用することです。場合によっては、このフラグをオンにすることでテキストの可読性に関する問題が解決することがあります。現在のところ、このフラグの使用は TTF フォントに対してのみ効果があり、これらのフォントがソース文書で使用されている場合に適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

新しいイメージングエンジンが使用されるかどうかを決定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値 @deprecated UseNewImagingEngine は非推奨です |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |
