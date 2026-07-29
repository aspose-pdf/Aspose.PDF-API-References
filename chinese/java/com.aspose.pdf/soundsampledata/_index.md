---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Aspose.PDF for Java API 参考"
description: "表示特定于声音对象的附加条目（第 9.2 节 PDF1-7）"
type: docs
weight: 4580
url: /zh/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

表示特定于声音对象的附加条目（第 9.2 节 PDF1-7）

## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | 编码格式的默认值。 |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | BitsPerchannel 参数的默认值。 |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Channels 参数的默认值。 |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | SamplingRate 的默认值。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | 初始化新的声音样本数据。 |
| [SoundSampleData](#SoundSampleData-long-int-) | 初始化新的声音样本数据。 |
| [SoundSampleData](#SoundSampleData-long-int-int-) | 初始化新的声音样本数据。 |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | 初始化新的声音样本数据。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | 获取每个通道每个样本值的位数。 |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | 获取编码格式。 |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | 获取声音通道的数量。 |
| [getSamplingRate](#getSamplingRate--) | 获取采样率。 |
| [setBitsPerChannel](#setBitsPerChannel-int-) | 设置每个通道每个样本值的位数。 |
| [setEncodingFormat](#setEncodingFormat-int-) | 设置编码格式。 |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | 设置声音通道的数量。 |
| [setSamplingRate](#setSamplingRate-long-) | 设置采样率。 |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

编码格式的默认值。

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

BitsPerchannel 参数的默认值。

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Channels 参数的默认值。

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

SamplingRate 的默认值。

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

初始化新的声音样本数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate |  | 采样率。 |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

初始化新的声音样本数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate |  | 采样率。 |
| numberOfSoundChannels |  | 声音通道的数量。 |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

初始化新的声音样本数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate |  | 采样率。 |
| numberOfSoundChannels |  | 声音通道的数量。 |
| bitsPerChannel |  | 每个通道每个样本值的位数。 |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

初始化新的声音样本数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate |  | 采样率。 |
| numberOfSoundChannels |  | 声音通道的数量。 |
| bitsPerChannel |  | 每个通道每个样本值的位数。 |
| soundSampleDataEncodingFormat |  | 样本数据的编码格式。 |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

获取每个通道每个样本值的位数。

**Returns:**
int 值

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

获取编码格式。

**Returns:**
SoundSampleDataEncodingFormat 值 @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

获取声音通道的数量。

**Returns:**
int 值

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

获取采样率。

**Returns:**
长整型值

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

设置每个通道每个样本值的位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

设置编码格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | SoundSampleDataEncodingFormat 值 @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

设置声音通道的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

设置采样率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 长整型值 |
