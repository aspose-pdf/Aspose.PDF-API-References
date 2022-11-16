---
title: SoundSampleData
second_title: Aspose.PDF для справки по Java API
description: Представляет дополнительные записи, относящиеся к звуковому объекту Раздел 9.2 PDF1-7
type: docs
weight: 331
url: /ru/java/com.aspose.pdf/soundsampledata/
---
**Наследование:**
java.lang.Object
```
public class SoundSampleData
```

Представляет дополнительные записи, относящиеся к звуковому объекту (Раздел 9.2 PDF1-7)
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SoundSampleData(long samplingRate)](#SoundSampleData-long-) | Инициализирует новые данные звукового образца. |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels)](#SoundSampleData-long-int-) | Инициализирует новые данные звукового образца. |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)](#SoundSampleData-long-int-int-) | Инициализирует новые данные звукового образца. |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)](#SoundSampleData-long-int-int-int-) | Инициализирует новые данные звукового образца. |
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT-ENCODING-FORMAT) | Значение по умолчанию для формата кодирования. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT-OF-BITS-PER-CHANNEL) | Значение по умолчанию для параметра BitsPerchannel. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT-OF-SOUND-CHANNELS) | Значение по умолчанию для параметра Каналы. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT-SAMPLING-RATE) | Значение по умолчанию для SamplingRate. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Получает количество битов на значение выборки на канал. |
| [getClass()](#getClass--) |  |
| [getEncodingFormat_Rename_Namesake()](#getEncodingFormat-Rename-Namesake--) | Получает формат кодировки. |
| [getNumberOfSoundChannels()](#getNumberOfSoundChannels--) | Получает количество звуковых каналов. |
| [getSamplingRate()](#getSamplingRate--) | Получает частоту дискретизации. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(int value)](#setBitsPerChannel-int-) | Устанавливает количество битов на значение выборки на канал. |
| [setEncodingFormat(int value)](#setEncodingFormat-int-) | Устанавливает формат кодирования. |
| [setNumberOfSoundChannels(int value)](#setNumberOfSoundChannels-int-) | Устанавливает количество звуковых каналов. |
| [setSamplingRate(long value)](#setSamplingRate-long-) | Устанавливает частоту дискретизации. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoundSampleData(long samplingRate) {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```


Инициализирует новые данные звукового образца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| samplingRate | long | Частота дискретизации. |

### SoundSampleData(long samplingRate, int numberOfSoundChannels) {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```


Инициализирует новые данные звукового образца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| samplingRate | long | Частота дискретизации. |
| numberOfSoundChannels | int | Количество звуковых каналов. |

### SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel) {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```


Инициализирует новые данные звукового образца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| samplingRate | long | Частота дискретизации. |
| numberOfSoundChannels | int | Количество звуковых каналов. |
| bitsPerChannel | int | Количество битов на выборочное значение на канал. |

### SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat) {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```


Инициализирует новые данные звукового образца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| samplingRate | long | Частота дискретизации. |
| numberOfSoundChannels | int | Количество звуковых каналов. |
| bitsPerChannel | int | Количество битов на выборочное значение на канал. |
| soundSampleDataEncodingFormat | int | Формат кодирования демонстрационных данных. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT-ENCODING-FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```


Значение по умолчанию для формата кодирования.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT-OF-BITS-PER-CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```


Значение по умолчанию для параметра BitsPerchannel.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT-OF-SOUND-CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```


Значение по умолчанию для параметра Каналы.

### DEFAULT_SAMPLING_RATE {#DEFAULT-SAMPLING-RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```


Значение по умолчанию для SamplingRate.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getBitsPerChannel() {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```


Получает количество битов на значение выборки на канал.

**Возвращает:**
интервал - целочисленное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEncodingFormat_Rename_Namesake() {#getEncodingFormat-Rename-Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```


Получает формат кодировки.

**Возвращает:**
int — значение SoundSampleDataEncodingFormat
### getNumberOfSoundChannels() {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```


Получает количество звуковых каналов.

**Возвращает:**
интервал - целочисленное значение
### getSamplingRate() {#getSamplingRate--}
```
public long getSamplingRate()
```


Получает частоту дискретизации.

**Возвращает:**
длинное - длинное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
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


Устанавливает количество битов на значение выборки на канал.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setEncodingFormat(int value) {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```


Устанавливает формат кодирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels(int value) {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```


Устанавливает количество звуковых каналов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setSamplingRate(long value) {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```


Устанавливает частоту дискретизации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | длинное значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
