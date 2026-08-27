---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、統一された変換方式（統一内部ドキュメントモデルを使用）で保存するための保存オプションを表します。"
type: docs
weight: 5420
url: /ja/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

このクラスは、統一された変換方式（統一内部ドキュメントモデルを使用）で保存するための保存オプションを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | 数スレッドでページを処理します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | 変換中に動作し、内部変換ステージの変換イベントを外部の総進行イベントに変換する内部プログレスイベントプロセッサを表します。また、このクラスは不要になったリソースを解放できるようにイベントをブロードキャストします。この内部クラスは PDF から APS、そして APS から [Other format] への進行イベントを処理し、総進行を計算して顧客のコードにその総進行イベントを通知します。このクラスは二種類のイベントを使用します：ApsToExternal モデル変換と PDF から APS への変換イベントで、総進行イベントを生成します。エクスポートは三段階です：1) PDF から APS、2) APS 認識、3) APS をターゲット形式へエクスポート。コンストラクタは、変換するページ数や各ステージが総進行の中で占める概算割合を調整できるようにします。 |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | この属性は、OCR サブレイヤーを使用して PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。値: {@code true} の場合、テキストは結果ドキュメントに抽出されます。{@code false} の場合は抽出されません。 |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数並べて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例: DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジのスムージング（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、必要なときにのみこのオプションを使用してください。 |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> この属性は、OCR サブレイヤーを使用して PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 </p>Value: {@code true} テキストは結果ドキュメントに抽出されます。{@code false} の場合は抽出されません。 <hr> デフォルト値 == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | 変換中に動作し、内部変換ステージの変換イベントを外部の総進行イベントに変換する内部プログレスイベントプロセッサを表します。また、このクラスは不要になったリソースを解放できるようにイベントをブロードキャストします。この内部クラスは PDF から APS、そして APS から [Other format] への進行イベントを処理し、総進行を計算して顧客のコードにその総進行イベントを通知します。このクラスは二種類のイベントを使用します：ApsToExternal モデル変換と PDF から APS への変換イベントで、総進行イベントを生成します。エクスポートは三段階です：1) PDF から APS、2) APS 認識、3) APS をターゲット形式へエクスポート。コンストラクタは、変換するページ数や各ステージが総進行の中で占める概算割合を調整できるようにします。 |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数並べて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例: DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジのスムージング（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、必要なときにのみこのオプションを使用してください。 |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

数スレッドでページを処理します。

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

変換中に動作し、内部変換ステージの変換イベントを外部の総進行イベントに変換する内部プログレスイベントプロセッサを表します。また、このクラスは不要になったリソースを解放できるようにイベントをブロードキャストします。この内部クラスは PDF から APS、そして APS から [Other format] への進行イベントを処理し、総進行を計算して顧客のコードにその総進行イベントを通知します。このクラスは二種類のイベントを使用します：ApsToExternal モデル変換と PDF から APS への変換イベントで、総進行イベントを生成します。エクスポートは三段階です：1) PDF から APS、2) APS 認識、3) APS をターゲット形式へエクスポート。コンストラクタは、変換するページ数や各ステージが総進行の中で占める概算割合を調整できるようにします。

**Returns:**
ConversionProgressEventsTranslator インスタンス

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

この属性は、OCR サブレイヤーを使用して PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。値: {@code true} の場合、テキストは結果ドキュメントに抽出されます。{@code false} の場合は抽出されません。

**Returns:**
ブール値

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数並べて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例: DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジのスムージング（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、必要なときにのみこのオプションを使用してください。

**Returns:**
ブール値

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> この属性は、OCR サブレイヤーを使用して PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 </p>Value: {@code true} テキストは結果ドキュメントに抽出されます。{@code false} の場合は抽出されません。 <hr> デフォルト値 == false

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
変換中に動作し、内部変換ステージの変換イベントを外部の総進行イベントに変換する内部プログレスイベントプロセッサを表します。また、このクラスは不要になったリソースを解放できるようにイベントをブロードキャストします。この内部クラスは PDF から APS、そして APS から [Other format] への進行イベントを処理し、総進行を計算して顧客のコードにその総進行イベントを通知します。このクラスは二種類のイベントを使用します：ApsToExternal モデル変換と PDF から APS への変換イベントで、総進行イベントを生成します。エクスポートは三段階です：1) PDF から APS、2) APS 認識、3) APS をターゲット形式へエクスポート。コンストラクタは、変換するページ数や各ステージが総進行の中で占める概算割合を調整できるようにします。

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数並べて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例: DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジのスムージング（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、必要なときにのみこのオプションを使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | ブール値 |
