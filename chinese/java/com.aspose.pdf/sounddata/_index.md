---
title: "SoundData"
linktitle: "SoundData"
second_title: "Aspose.PDF for Java API 参考"
description: "表示定义在激活注释时播放的声音的数据。"
type: docs
weight: 4540
url: /zh/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

表示定义在激活注释时播放的声音的数据。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBits](#getBits--) | 获取每个通道每个样本值的位数。 |
| [getChannels](#getChannels--) | 获取声音通道的数量。 |
| [getContents](#getContents--) | 获取在注释激活时播放的声音流。 |
| [getContentsInternal](#getContentsInternal--) | 获取在注释激活时播放的声音流。 |
| [getEncoding](#getEncoding--) | 获取样本数据的编码格式。 |
| [getRate](#getRate--) | 获取采样率（每秒样本数）。 |
| [setBits](#setBits-int-) | 设置每个通道每个样本值的位数。 |
| [setChannels](#setChannels-int-) | 设置声音通道的数量。 |
| [setEncoding](#setEncoding-int-) | 设置样本数据的编码格式。 |
| [setRate](#setRate-int-) | 设置采样率（每秒样本数）。 |

### getBits {#getBits--}
```
public int getBits()
```

获取每个通道每个样本值的位数。

**Returns:**
int 值 位数

### getChannels {#getChannels--}
```
public int getChannels()
```

获取声音通道的数量。

**Returns:**
声音通道的数量。

### getContents {#getContents--}
```
public InputStream getContents()
```

获取在注释激活时播放的声音流。

**Returns:**
InputStream 值

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

获取在注释激活时播放的声音流。

**Returns:**
Stream 值

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

获取样本数据的编码格式。

**Returns:**
SoundEncoding 值 @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

获取采样率（每秒样本数）。

**Returns:**
int 值

### setBits {#setBits-int-}
```
public void setBits(int value)
```

设置每个通道每个样本值的位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 位数 |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

设置声音通道的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 声音通道的数量。 |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

设置样本数据的编码格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | SoundEncoding 值 @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

设置采样率（每秒样本数）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
