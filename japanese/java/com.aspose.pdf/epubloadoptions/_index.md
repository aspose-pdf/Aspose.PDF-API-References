---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "EPUB ファイルを PDF 文書にロード/インポートするためのオプションを含みます。"
type: docs
weight: 1220
url: /ja/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

EPUB ファイルを PDF 文書にロード/インポートするためのオプションを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | EPUB ファイルを PDF ドキュメントに変換するためのデフォルトのロードオプションを作成します。デフォルトの PDF ページサイズは A4、300dpi、2480 × 3508 です。 |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | EPUB ファイルを PDF ドキュメントに変換するためのデフォルトのロードオプションを作成します。デフォルトの PDF ページサイズは A4、300dpi、2480 × 3508 です。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Epub ドキュメントを開く際に適用するカスタム CSS を取得または設定します。 |
| [getEngineType](#getEngineType--) | EPUB から PDF への変換エンジンタイプを選択します。デフォルトは EngineType.NEW です。 |
| [getMargin](#getMargin--) | 余白情報を表すオブジェクトへの参照を取得します。 |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | 余白領域の使用モードを表します。インポートされたドキュメントの余白使用に関連する CSS の指示（存在する場合）の処理方法を定義します。 |
| [getPageSize](#getPageSize--) | インポート用の出力ページサイズを取得します。 |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | 注意！この機能は実装済みですが、サンプルドキュメントでOSHARED層のブロッカー問題が判明したため、まだパブリックAPIに公開されていません。変換時のページサイズの使用モードを表します。HTML、EPUB などのフォーマットは通常フロート設計であり、必要なページサイズに合わせることができます。しかし、コンテンツに指定された水平位置やサイズがあり、必要なページサイズに収められない場合があります。そのような場合、（たとえばコンテンツのサイズが結果の PDF ドキュメントの初期ページサイズに合わないとき）何をすべきかを定義できます。 |
| [setCustomCss](#setCustomCss-java.lang.String-) | Epub ドキュメントを開く際に適用するカスタム CSS を取得または設定します。 |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | EPUB から PDF への変換エンジンタイプを選択します。デフォルトは EngineType.NEW です。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 余白情報を表すオブジェクトへの参照を取得します。 |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | 余白領域の使用モードを表します。インポートされたドキュメントの余白使用に関連する CSS の指示（存在する場合）の処理方法を定義します。 |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | 注意！この機能は実装済みですが、サンプルドキュメントでOSHARED層のブロッカー問題が判明したため、まだパブリックAPIに公開されていません。変換時のページサイズの使用モードを表します。HTML、EPUB などのフォーマットは通常フロート設計であり、必要なページサイズに合わせることができます。しかし、コンテンツに指定された水平位置やサイズがあり、必要なページサイズに収められない場合があります。そのような場合、（たとえばコンテンツのサイズが結果の PDF ドキュメントの初期ページサイズに合わないとき）何をすべきかを定義できます。 |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

EPUB ファイルを PDF ドキュメントに変換するためのデフォルトのロードオプションを作成します。デフォルトの PDF ページサイズは A4、300dpi、2480 × 3508 です。

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
EPUB ファイルを PDF ドキュメントに変換するためのデフォルトのロードオプションを作成します。デフォルトの PDF ページサイズは A4、300dpi、2480 × 3508 です。

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Epub ドキュメントを開く際に適用するカスタム CSS を取得または設定します。

**Returns:**
文字列値

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

EPUB から PDF への変換エンジンタイプを選択します。デフォルトは EngineType.NEW です。

**Returns:**
EngineType 要素

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

余白情報を表すオブジェクトへの参照を取得します。

**Returns:**
MarginInfo オブジェクト

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

余白領域の使用モードを表します。インポートされたドキュメントの余白使用に関連する CSS の指示（存在する場合）の処理方法を定義します。

**Returns:**
MarginsAreaUsageModes 値 @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

インポート用の出力ページサイズを取得します。

**Returns:**
Dimension2D オブジェクト

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

注意！この機能は実装済みですが、サンプルドキュメントでOSHARED層のブロッカー問題が判明したため、まだパブリックAPIに公開されていません。変換時のページサイズの使用モードを表します。HTML、EPUB などのフォーマットは通常フロート設計であり、必要なページサイズに合わせることができます。しかし、コンテンツに指定された水平位置やサイズがあり、必要なページサイズに収められない場合があります。そのような場合、（たとえばコンテンツのサイズが結果の PDF ドキュメントの初期ページサイズに合わないとき）何をすべきかを定義できます。

**Returns:**
PageSizeAdjustmentModes 値 @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Epub ドキュメントを開く際に適用するカスタム CSS を取得または設定します。

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
EPUB から PDF への変換エンジンタイプを選択します。デフォルトは EngineType.NEW です。

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
余白情報を表すオブジェクトへの参照を取得します。

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

余白領域の使用モードを表します。インポートされたドキュメントの余白使用に関連する CSS の指示（存在する場合）の処理方法を定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| marginsAreaUsageMode |  | MarginsAreaUsageModes 値 @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

注意！この機能は実装済みですが、サンプルドキュメントでOSHARED層のブロッカー問題が判明したため、まだパブリックAPIに公開されていません。変換時のページサイズの使用モードを表します。HTML、EPUB などのフォーマットは通常フロート設計であり、必要なページサイズに合わせることができます。しかし、コンテンツに指定された水平位置やサイズがあり、必要なページサイズに収められない場合があります。そのような場合、（たとえばコンテンツのサイズが結果の PDF ドキュメントの初期ページサイズに合わないとき）何をすべきかを定義できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | PageSizeAdjustmentModes 値 @see PageSizeAdjustmentModes |
