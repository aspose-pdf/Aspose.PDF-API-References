---
title: "SoundData"
linktitle: "SoundData"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "注釈がアクティブになったときに再生される音声を定義するサウンドデータを表します。"
type: docs
weight: 4540
url: /ja/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

注釈がアクティブになったときに再生される音声を定義するサウンドデータを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBits](#getBits--) | サンプル値あたりのビット数（チャンネルごと）を取得します。 |
| [getChannels](#getChannels--) | サウンドチャンネル数を取得します。 |
| [getContents](#getContents--) | アノテーションが有効化されたときに再生されるサウンドのストリームを取得します。 |
| [getContentsInternal](#getContentsInternal--) | アノテーションが有効化されたときに再生されるサウンドのストリームを取得します。 |
| [getEncoding](#getEncoding--) | サンプルデータのエンコーディング形式を取得します。 |
| [getRate](#getRate--) | サンプリングレート（1秒あたりのサンプル数）を取得します。 |
| [setBits](#setBits-int-) | サンプル値あたりのビット数（チャンネルごと）を設定します。 |
| [setChannels](#setChannels-int-) | サウンドチャンネル数を設定します。 |
| [setEncoding](#setEncoding-int-) | サンプルデータのエンコーディング形式を設定します。 |
| [setRate](#setRate-int-) | サンプリングレート（1秒あたりのサンプル数）を設定します。 |

### getBits {#getBits--}
```
public int getBits()
```

サンプル値あたりのビット数（チャンネルごと）を取得します。

**Returns:**
int 値 ビット数

### getChannels {#getChannels--}
```
public int getChannels()
```

サウンドチャンネル数を取得します。

**Returns:**
サウンドチャンネル数です。

### getContents {#getContents--}
```
public InputStream getContents()
```

アノテーションが有効化されたときに再生されるサウンドのストリームを取得します。

**Returns:**
InputStream 値

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

アノテーションが有効化されたときに再生されるサウンドのストリームを取得します。

**Returns:**
Stream 値

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

サンプルデータのエンコーディング形式を取得します。

**Returns:**
SoundEncoding 値 @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

サンプリングレート（1秒あたりのサンプル数）を取得します。

**Returns:**
int 値です。

### setBits {#setBits-int-}
```
public void setBits(int value)
```

サンプル値あたりのビット数（チャンネルごと）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ビット数 |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

サウンドチャンネル数を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | サウンドチャンネル数です。 |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

サンプルデータのエンコーディング形式を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | SoundEncoding 値 @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

サンプリングレート（1秒あたりのサンプル数）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
