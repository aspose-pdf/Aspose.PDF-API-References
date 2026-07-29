---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PCLファイルをPDF文書にロード（インポート）するためのオプションを表します。"
type: docs
weight: 3530
url: /ja/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

PCLファイルをPDF文書にロード（インポート）するためのオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | {@code PclLoadOptions} オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBatchSize](#getBatchSize--) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [getConversionEngine](#getConversionEngine--) | 変換に使用される変換エンジンを定義します。 |
| [getExceptions](#getExceptions--) | 変換エラーの一覧。 |
| [isSupressErrors](#isSupressErrors--) | PCL 変換エラーを抑制すべきかどうかを示すブール値を取得または設定します。 |
| [setBatchSize](#setBatchSize-int-) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [setConversionEngine](#setConversionEngine-int-) | 変換に使用される変換エンジンを定義します。 |
| [setSupressErrors](#setSupressErrors-boolean-) | PCL 変換エラーを抑制すべきかどうかを示すブール値を取得または設定します。 |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

{@code PclLoadOptions} オブジェクトを作成します。

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Returns:**
int 値です。

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

変換に使用される変換エンジンを定義します。

**Returns:**
ConversionEngines 要素 @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

変換エラーの一覧。

**Returns:**
例外の一覧

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

PCL 変換エラーを抑制すべきかどうかを示すブール値を取得または設定します。

**Returns:**
ブール値

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

変換に使用される変換エンジンを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines 要素 @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

PCL 変換エラーを抑制すべきかどうかを示すブール値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| supressErrors |  | ブール値 |
