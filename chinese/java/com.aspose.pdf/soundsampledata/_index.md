---
title: SoundSampleData
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示特定于声音对象的附加条目第 9.2 节 PDF1-7
type: docs
weight: 331
url: /zh/java/com.aspose.pdf/soundsampledata/
---
**遗产：**
java.lang.Object
```
public class SoundSampleData
```

表示特定于声音对象的附加条目（第 9.2 节 PDF1-7）
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SoundSampleData(long samplingRate)](#SoundSampleData-long-) | 初始化新的声音样本数据。 |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels)](#SoundSampleData-long-int-) | 初始化新的声音样本数据。 |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)](#SoundSampleData-long-int-int-) | 初始化新的声音样本数据。 |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)](#SoundSampleData-long-int-int-int-) | 初始化新的声音样本数据。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT-ENCODING-FORMAT) | 编码格式的默认值。 |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT-OF-BITS-PER-CHANNEL) | BitsPerchannel 参数的默认值。 |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT-OF-SOUND-CHANNELS) | 通道参数的默认值。 |
| [DEFAULT_SAMPLING_RATE](#DEFAULT-SAMPLING-RATE) | 采样率的默认值。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | 获取每个通道每个样本值的位数。 |
| [getClass()](#getClass--) |  |
| [getEncodingFormat_Rename_Namesake()](#getEncodingFormat-Rename-Namesake--) | 获取编码格式。 |
| [getNumberOfSoundChannels()](#getNumberOfSoundChannels--) | 获取声道数。 |
| [getSamplingRate()](#getSamplingRate--) | 获取采样率。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(int value)](#setBitsPerChannel-int-) | 设置每个通道每个样本值的位数。 |
| [setEncodingFormat(int value)](#setEncodingFormat-int-) | 设置编码格式。 |
| [setNumberOfSoundChannels(int value)](#setNumberOfSoundChannels-int-) | 设置声道数。 |
| [setSamplingRate(long value)](#setSamplingRate-long-) | 设置采样率。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoundSampleData(long samplingRate) {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```


初始化新的声音样本数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate | long | 采样率。 |

### SoundSampleData(long samplingRate, int numberOfSoundChannels) {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```


初始化新的声音样本数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate | long | 采样率。 |
| numberOfSoundChannels | int | 声道数。 |

### SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel) {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```


初始化新的声音样本数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate | long | 采样率。 |
| numberOfSoundChannels | int | 声道数。 |
| bitsPerChannel | int | 每个通道每个样本值的位数。 |

### SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat) {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```


初始化新的声音样本数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| samplingRate | long | 采样率。 |
| numberOfSoundChannels | int | 声道数。 |
| bitsPerChannel | int | 每个通道每个样本值的位数。 |
| soundSampleDataEncodingFormat | int | 示例数据的编码格式。 |

### DEFAULT_ENCODING_FORMAT {#DEFAULT-ENCODING-FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```


编码格式的默认值。

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT-OF-BITS-PER-CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```


BitsPerchannel 参数的默认值。

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT-OF-SOUND-CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```


通道参数的默认值。

### DEFAULT_SAMPLING_RATE {#DEFAULT-SAMPLING-RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```


采样率的默认值。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getBitsPerChannel() {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```


获取每个通道每个样本值的位数。

**退货：**
int - 整数值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEncodingFormat_Rename_Namesake() {#getEncodingFormat-Rename-Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```


获取编码格式。

**退货：**
int - SoundSampleDataEncodingFormat 值
### getNumberOfSoundChannels() {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```


获取声道数。

**退货：**
int - 整数值
### getSamplingRate() {#getSamplingRate--}
```
public long getSamplingRate()
```


获取采样率。

**退货：**
多头价值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitsPerChannel(int value) {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```


设置每个通道每个样本值的位数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setEncodingFormat(int value) {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```


设置编码格式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | SoundSampleDataEncodingFormat 值 |

### setNumberOfSoundChannels(int value) {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```


设置声道数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setSamplingRate(long value) {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```


设置采样率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 长值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
