---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントの変換オプションのセットを表します"
type: docs
weight: 3730
url: /ja/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

PDF ドキュメントの変換オプションのセットを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | コンストラクタ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | コンストラクタ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | コンストラクタ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | コンストラクタ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | コンストラクタ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | テキストを揃える戦略です。このパラメーターはフラグ {@code AlignText} が true に設定されている場合にのみ意味があります。 |
| [getAlignText](#getAlignText--) | このフラグは変換後のドキュメントにおけるテキストの配置を制御します。デフォルトでは、ドキュメント変換はテキスト配置に影響せず、テキストはそのまま保持されます。しかし、フォント置換により変換後のドキュメントでテキストが重なったり余分なスペースが生じる場合があります。このフラグが設定されると、特別な配置操作が実行されます。このフラグは、テキストが重なっている、または余分なスペースがあるドキュメントにのみ設定すべきです。使用するとパフォーマンスが低下し、場合によってはテキスト内容が破損する可能性があります。 |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | PDF 形式変換中の自動タグ付け設定を取得または設定します。自動タグ付け設定は、特定の PDF 形式への変換時に PDF ドキュメントのアクセシビリティと構造を向上させるために通常使用される自動タグ付けプロセスの動作を構成するために使用されます。 |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | ソフトマスク付き画像に対するアクションです。 |
| [getDefault](#getDefault--) | デフォルトパラメーターを持つ PdfFormatConversionOptions オブジェクトを取得します |
| [getErrorAction](#getErrorAction--) | 変換できないオブジェクトに対するアクションです |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | 余分なフォントを除外し、ドキュメントのファイルサイズを削減する戦略です。このパラメーターはフラグ {@code OptimizeFileSize} が true に設定されている場合にのみ意味があります。デフォルトでは、{@code SubsetFonts} と {@code RemoveDuplicatedFonts} の組み合わせが使用されます。 |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | 一部のフォントを PDF ドキュメントに埋め込めない場合のオプションです。 |
| [getFormat](#getFormat--) | PDF 形式です。 |
| [getIccProfileFileName](#getIccProfileFileName--) | icc プロファイル名のファイル名を取得します。null の場合はデフォルトの icc プロファイルが使用されます。 |
| [getLogFileName](#getLogFileName--) | コメントが保存されるファイルへのパスです。 |
| [getLogStream](#getLogStream--) | コメントが保存されるストリームです。 |
| [getNonSpecificationCases](#getNonSpecificationCases--) | ソースドキュメントが PDF/A 仕様に準拠していない場合の PDF/A 変換プロセスを制御するフラグを保持します。 |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | このプロパティは出力プロパティです。最後の PDF/A 変換時にコンピューター上で見つからなかったすべてのフォント（フォント名）を保持します。 |
| [getOptimizeFileSize](#getOptimizeFileSize--) | ファイルサイズが削減された PDF/A ドキュメントを取得するための特殊変換モードを有効化/無効化するフラグを取得します。このフラグは現在、PDF ドキュメントで使用されるフォントの最適化に影響しますが、将来的にはグラフィックなどの他のデータ構造の最適化を有効にするためにも使用される可能性があります。このフラグとモードの組み合わせにより、ファイルサイズは大幅に削減できる一方で、変換のパフォーマンスが大幅に低下する可能性があります。 |
| [getOutputIntent](#getOutputIntent--) | PDF 形式変換のための {@link OutputIntent} を取得または設定します。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）は、PDF ドキュメントが作成される対象の出力デバイスまたは条件を指定します。これにより、ドキュメント内の色がターゲットデバイスで正しく表示されるようにします。 |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Unicode Private Use Area (PUA) のシンボルを処理する戦略です。 |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | シンボリック TrueType フォントが複数のエンコーディングサブテーブルを持つ場合に、シンボリックフォントのエンコーディングデータをコピーする戦略です。 |
| [getTransparencyAction](#getTransparencyAction--) | 画像マスクオブジェクトに対するアクションです |
| [getTransparencyResolution](#getTransparencyResolution--) | 透過画像の変換中に解像度を設定します。解像度が高いほど変換速度は遅くなります。デフォルト値は 300 です。 |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Unicode マッピングの問題を解決するためのルールです。null にすることも可能です。 |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | 非同期モードで画像ストリームの実行を取得/設定します。 |
| [isLowMemoryMode](#isLowMemoryMode--) | 低メモリ変換モードは有効ですか |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | ページ単位でのフォント解析モードが有効かどうか デフォルト値 = false |
| [isTransferInfo](#isTransferInfo--) | PDF 2.0 に変換した際に Info から Metadata へデータを渡すかどうかを取得または設定します。デフォルトは true です。 |
| [isTransparencyIgnore](#isTransparencyIgnore--) | デフォルト値は FALSE で、透明色は文書の外観を維持するために処理されます。値が TRUE の場合、透明色は非透明に変換され、一部のオブジェクトが覆われる可能性があります。 |
| [setAlignStrategy](#setAlignStrategy-byte-) | テキストを揃える戦略です。このパラメーターはフラグ {@code AlignText} が true に設定されている場合にのみ意味があります。 |
| [setAlignText](#setAlignText-boolean-) | このフラグは変換後のドキュメントにおけるテキストの配置を制御します。デフォルトでは、ドキュメント変換はテキスト配置に影響せず、テキストはそのまま保持されます。しかし、フォント置換により変換後のドキュメントでテキストが重なったり余分なスペースが生じる場合があります。このフラグが設定されると、特別な配置操作が実行されます。このフラグは、テキストが重なっている、または余分なスペースがあるドキュメントにのみ設定すべきです。使用するとパフォーマンスが低下し、場合によってはテキスト内容が破損する可能性があります。 |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | 非同期モードで画像ストリームの実行を取得/設定します。 |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | PDF 形式変換中の自動タグ付け設定を取得または設定します。自動タグ付け設定は、特定の PDF 形式への変換時に PDF ドキュメントのアクセシビリティと構造を向上させるために通常使用される自動タグ付けプロセスの動作を構成するために使用されます。 |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | ソフトマスク付き画像に対するアクションです。 |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | 変換できないオブジェクトに対するアクションです |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | 余分なフォントを除外し、ドキュメントのファイルサイズを削減する戦略です。このパラメーターはフラグ {@code OptimizeFileSize} が true に設定されている場合にのみ意味があります。デフォルトでは、{@code SubsetFonts} と {@code RemoveDuplicatedFonts} の組み合わせが使用されます。 |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | PDF 形式です。 |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | ICC プロファイル名のファイル名を設定します。null の場合はデフォルトの ICC プロファイルが使用されます。 |
| [setLogFileName](#setLogFileName-java.lang.String-) | コメントが保存されるファイルへのパスです。 |
| [setLogStream](#setLogStream-java.io.OutputStream-) | コメントが保存されるストリームです。 |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | 低メモリ変換モードは有効ですか |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | ファイルサイズが削減された PDF/A ドキュメントを取得するための特殊変換モードを有効/無効にするフラグを設定します。このフラグは現在、PDF ドキュメントで使用されるフォントの最適化に影響しますが、将来的にはグラフィックなどの他のデータ構造の最適化にも使用される可能性があります。このフラグとモードの組み合わせはファイルサイズを大幅に削減できますが、同時に変換パフォーマンスを大幅に低下させる可能性があります。 |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | PDF 形式変換のための {@link OutputIntent} を取得または設定します。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）は、PDF ドキュメントが作成される対象の出力デバイスまたは条件を指定します。これにより、ドキュメント内の色がターゲットデバイスで正しく表示されるようにします。 |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | ページ単位でのフォント解析モードを有効に設定します デフォルト値 = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Unicode Private Use Area (PUA) のシンボルを処理する戦略です。 |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | シンボリック TrueType フォントが複数のエンコーディングサブテーブルを持つ場合に、シンボリックフォントのエンコーディングデータをコピーする戦略です。 |
| [setTransferInfo](#setTransferInfo-boolean-) | PDF 2.0 に変換した際に Info から Metadata へデータを渡すかどうかを取得または設定します。デフォルトは true です。 |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | 画像マスクオブジェクトに対するアクションです |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | デフォルト値は FALSE で、透明色は文書の外観を維持するために処理されます。値が TRUE の場合、透明色は非透明に変換され、一部のオブジェクトが覆われる可能性があります。 |
| [setTransparencyResolution](#setTransparencyResolution-int-) | 透過画像の変換中に解像度を設定します。解像度が高いほど変換速度は遅くなります。デフォルト値は 300 です。 |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Unicode マッピングの問題を解決するためのルールです。null にすることも可能です。 |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
コンストラクタ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
コンストラクタ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
コンストラクタ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
コンストラクタ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
コンストラクタ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
コンストラクタ

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

テキストを揃える戦略です。このパラメーターはフラグ {@code AlignText} が true に設定されている場合にのみ意味があります。

**Returns:**
SegmentAlignStrategy 要素 @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

このフラグは変換後のドキュメントにおけるテキストの配置を制御します。デフォルトでは、ドキュメント変換はテキスト配置に影響せず、テキストはそのまま保持されます。しかし、フォント置換により変換後のドキュメントでテキストが重なったり余分なスペースが生じる場合があります。このフラグが設定されると、特別な配置操作が実行されます。このフラグは、テキストが重なっている、または余分なスペースがあるドキュメントにのみ設定すべきです。使用するとパフォーマンスが低下し、場合によってはテキスト内容が破損する可能性があります。

**Returns:**
ブール値

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

PDF 形式変換中の自動タグ付け設定を取得または設定します。自動タグ付け設定は、特定の PDF 形式への変換時に PDF ドキュメントのアクセシビリティと構造を向上させるために通常使用される自動タグ付けプロセスの動作を構成するために使用されます。

**Returns:**
AutoTaggingSettings インスタンス

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

ソフトマスク付き画像に対するアクションです。

**Returns:**
int 値です。

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

デフォルトパラメーターを持つ PdfFormatConversionOptions オブジェクトを取得します

**Returns:**
PdfFormatConversionOptions オブジェクト

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

変換できないオブジェクトに対するアクションです

**Returns:**
ConvertErrorAction 要素 @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

余分なフォントを除外し、ドキュメントのファイルサイズを削減する戦略です。このパラメーターはフラグ {@code OptimizeFileSize} が true に設定されている場合にのみ意味があります。デフォルトでは、{@code SubsetFonts} と {@code RemoveDuplicatedFonts} の組み合わせが使用されます。

**Returns:**
バイト値 @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

一部のフォントを PDF ドキュメントに埋め込めない場合のオプションです。

**Returns:**
FontEmbeddingOptions オブジェクト

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

PDF 形式です。

**Returns:**
PdfFormat 要素 @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

icc プロファイル名のファイル名を取得します。null の場合はデフォルトの icc プロファイルが使用されます。

**Returns:**
String オブジェクト

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

コメントが保存されるファイルへのパスです。

**Returns:**
String オブジェクト

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

コメントが保存されるストリームです。

**Returns:**
OutputStream オブジェクト

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

ソースドキュメントが PDF/A 仕様に準拠していない場合の PDF/A 変換プロセスを制御するフラグを保持します。

**Returns:**
PdfANonSpecificationFlags オブジェクト

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

このプロパティは出力プロパティです。最後の PDF/A 変換時にコンピューター上で見つからなかったすべてのフォント（フォント名）を保持します。

**Returns:**
文字列の配列

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

ファイルサイズが削減された PDF/A ドキュメントを取得するための特殊変換モードを有効化/無効化するフラグを取得します。このフラグは現在、PDF ドキュメントで使用されるフォントの最適化に影響しますが、将来的にはグラフィックなどの他のデータ構造の最適化を有効にするためにも使用される可能性があります。このフラグとモードの組み合わせにより、ファイルサイズは大幅に削減できる一方で、変換のパフォーマンスが大幅に低下する可能性があります。

**Returns:**
ブール値

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

PDF 形式変換のための {@link OutputIntent} を取得または設定します。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）は、PDF ドキュメントが作成される対象の出力デバイスまたは条件を指定します。これにより、ドキュメント内の色がターゲットデバイスで正しく表示されるようにします。

**Returns:**
OutputIntent インスタンス

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Unicode Private Use Area (PUA) のシンボルを処理する戦略です。

**Returns:**
PuaProcessingStrategy 要素 @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

シンボリック TrueType フォントが複数のエンコーディングサブテーブルを持つ場合に、シンボリックフォントのエンコーディングデータをコピーする戦略です。

**Returns:**
PdfASymbolicFontEncodingStrategy オブジェクト

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

画像マスクオブジェクトに対するアクションです

**Returns:**
ConvertTransparencyAction 要素 @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

透過画像の変換中に解像度を設定します。解像度が高いほど変換速度は遅くなります。デフォルト値は 300 です。

**Returns:**
解像度の値

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Unicode マッピングの問題を解決するためのルールです。null にすることも可能です。

**Returns:**
ToUnicodeProcessingRules オブジェクト

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

非同期モードで画像ストリームの実行を取得/設定します。

**Returns:**
ブール値

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

低メモリ変換モードは有効ですか

**Returns:**
ブール値

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

ページ単位でのフォント解析モードが有効かどうか デフォルト値 = false

**Returns:**
ブール値

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

PDF 2.0 に変換した際に Info から Metadata へデータを渡すかどうかを取得または設定します。デフォルトは true です。

**Returns:**
ブール値

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

デフォルト値は FALSE で、透明色は文書の外観を維持するために処理されます。値が TRUE の場合、透明色は非透明に変換され、一部のオブジェクトが覆われる可能性があります。

**Returns:**
ブール値

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

テキストを揃える戦略です。このパラメーターはフラグ {@code AlignText} が true に設定されている場合にのみ意味があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alignStrategy |  | SegmentAlignStrategy 要素 @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

このフラグは変換後のドキュメントにおけるテキストの配置を制御します。デフォルトでは、ドキュメント変換はテキスト配置に影響せず、テキストはそのまま保持されます。しかし、フォント置換により変換後のドキュメントでテキストが重なったり余分なスペースが生じる場合があります。このフラグが設定されると、特別な配置操作が実行されます。このフラグは、テキストが重なっている、または余分なスペースがあるドキュメントにのみ設定すべきです。使用するとパフォーマンスが低下し、場合によってはテキスト内容が破損する可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

非同期モードで画像ストリームの実行を取得/設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
PDF 形式変換中の自動タグ付け設定を取得または設定します。自動タグ付け設定は、特定の PDF 形式への変換時に PDF ドキュメントのアクセシビリティと構造を向上させるために通常使用される自動タグ付けプロセスの動作を構成するために使用されます。

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
ソフトマスク付き画像に対するアクションです。

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
変換できないオブジェクトに対するアクションです

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

余分なフォントを除外し、ドキュメントのファイルサイズを削減する戦略です。このパラメーターはフラグ {@code OptimizeFileSize} が true に設定されている場合にのみ意味があります。デフォルトでは、{@code SubsetFonts} と {@code RemoveDuplicatedFonts} の組み合わせが使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
PDF 形式です。

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
ICC プロファイル名のファイル名を設定します。null の場合はデフォルトの ICC プロファイルが使用されます。

### setLogFileName {#setLogFileName-java.lang.String-}
コメントが保存されるファイルへのパスです。

### setLogStream {#setLogStream-java.io.OutputStream-}
コメントが保存されるストリームです。

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

低メモリ変換モードは有効ですか

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

ファイルサイズが削減された PDF/A ドキュメントを取得するための特殊変換モードを有効/無効にするフラグを設定します。このフラグは現在、PDF ドキュメントで使用されるフォントの最適化に影響しますが、将来的にはグラフィックなどの他のデータ構造の最適化にも使用される可能性があります。このフラグとモードの組み合わせはファイルサイズを大幅に削減できますが、同時に変換パフォーマンスを大幅に低下させる可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
PDF 形式変換のための {@link OutputIntent} を取得または設定します。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）は、PDF ドキュメントが作成される対象の出力デバイスまたは条件を指定します。これにより、ドキュメント内の色がターゲットデバイスで正しく表示されるようにします。

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

ページ単位でのフォント解析モードを有効に設定します デフォルト値 = false

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| b |  | ブール値 |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Unicode Private Use Area (PUA) のシンボルを処理する戦略です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PuaProcessingStrategy 要素 @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
シンボリック TrueType フォントが複数のエンコーディングサブテーブルを持つ場合に、シンボリックフォントのエンコーディングデータをコピーする戦略です。

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

PDF 2.0 に変換した際に Info から Metadata へデータを渡すかどうかを取得または設定します。デフォルトは true です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
画像マスクオブジェクトに対するアクションです

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

デフォルト値は FALSE で、透明色は文書の外観を維持するために処理されます。値が TRUE の場合、透明色は非透明に変換され、一部のオブジェクトが覆われる可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

透過画像の変換中に解像度を設定します。解像度が高いほど変換速度は遅くなります。デフォルト値は 300 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dpi |  | 解像度の値 |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Unicode マッピングの問題を解決するためのルールです。null にすることも可能です。
