---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "サウンドオブジェクトに固有の追加エントリを表します（セクション 9.2 PDF1-7）。"
type: docs
weight: 4580
url: /ja/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

サウンドオブジェクトに固有の追加エントリを表します（セクション 9.2 PDF1-7）。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | エンコーディング形式のデフォルト値です。 |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | BitsPerchannel パラメーターのデフォルト値です。 |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Channels パラメーターのデフォルト値です。 |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | SamplingRate のデフォルト値です。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | 新しいサウンドサンプルデータを初期化します。 |
| [SoundSampleData](#SoundSampleData-long-int-) | 新しいサウンドサンプルデータを初期化します。 |
| [SoundSampleData](#SoundSampleData-long-int-int-) | 新しいサウンドサンプルデータを初期化します。 |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | 新しいサウンドサンプルデータを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | サンプル値あたりのビット数（チャンネルごと）を取得します。 |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | エンコーディング形式を取得します。 |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | サウンドチャンネル数を取得します。 |
| [getSamplingRate](#getSamplingRate--) | サンプリングレートを取得します。 |
| [setBitsPerChannel](#setBitsPerChannel-int-) | サンプル値あたりのビット数（チャンネルごと）を設定します。 |
| [setEncodingFormat](#setEncodingFormat-int-) | エンコーディング形式を設定します。 |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | サウンドチャンネル数を設定します。 |
| [setSamplingRate](#setSamplingRate-long-) | サンプリングレートを設定します。 |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

エンコーディング形式のデフォルト値です。

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

BitsPerchannel パラメーターのデフォルト値です。

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Channels パラメーターのデフォルト値です。

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

SamplingRate のデフォルト値です。

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

新しいサウンドサンプルデータを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| samplingRate |  | サンプリングレートです。 |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

新しいサウンドサンプルデータを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| samplingRate |  | サンプリングレートです。 |
| numberOfSoundChannels |  | サウンドチャンネル数です。 |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

新しいサウンドサンプルデータを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| samplingRate |  | サンプリングレートです。 |
| numberOfSoundChannels |  | サウンドチャンネル数です。 |
| bitsPerChannel |  | チャンネルごとのサンプル値あたりのビット数です。 |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

新しいサウンドサンプルデータを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| samplingRate |  | サンプリングレートです。 |
| numberOfSoundChannels |  | サウンドチャンネル数です。 |
| bitsPerChannel |  | チャンネルごとのサンプル値あたりのビット数です。 |
| soundSampleDataEncodingFormat |  | サンプルデータのエンコーディング形式。 |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

サンプル値あたりのビット数（チャンネルごと）を取得します。

**Returns:**
int 値です。

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

エンコーディング形式を取得します。

**Returns:**
SoundSampleDataEncodingFormat の値 @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

サウンドチャンネル数を取得します。

**Returns:**
int 値です。

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

サンプリングレートを取得します。

**Returns:**
long 値

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

サンプル値あたりのビット数（チャンネルごと）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

エンコーディング形式を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | SoundSampleDataEncodingFormat の値 @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

サウンドチャンネル数を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

サンプリングレートを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | long 値 |
