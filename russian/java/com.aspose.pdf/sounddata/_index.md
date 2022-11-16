---
title: SoundData
second_title: Aspose.PDF для справки по Java API
description: Представляет звуковые данные, определяющие звук, который будет воспроизводиться при активации аннотации.
type: docs
weight: 327
url: /ru/java/com.aspose.pdf/sounddata/
---
**Наследование:**
java.lang.Object
```
public final class SoundData
```

Представляет звуковые данные, определяющие звук, который будет воспроизводиться при активации аннотации.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBits()](#getBits--) | Получает количество битов на значение выборки на канал. |
| [getChannels()](#getChannels--) | Получает количество звуковых каналов. |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | Получает поток звука, который будет воспроизводиться при активации аннотации. |
| [getContentsInternal()](#getContentsInternal--) | Получает поток звука, который будет воспроизводиться при активации аннотации. |
| [getEncoding()](#getEncoding--) | Получает формат кодировки для примера данных. |
| [getRate()](#getRate--) | Получает частоту дискретизации в выборках в секунду. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBits(int value)](#setBits-int-) | Устанавливает количество битов на значение выборки на канал. |
| [setChannels(int value)](#setChannels-int-) | Устанавливает количество звуковых каналов. |
| [setEncoding(int value)](#setEncoding-int-) | Устанавливает формат кодирования для демонстрационных данных. |
| [setRate(int value)](#setRate-int-) | Устанавливает частоту дискретизации в выборках в секунду. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBits() {#getBits--}
```
public int getBits()
```


Получает количество битов на значение выборки на канал.

**Возвращает:**
int - число битов значения int
### getChannels() {#getChannels--}
```
public int getChannels()
```


Получает количество звуковых каналов.

**Возвращает:**
int - Количество звуковых каналов.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContents() {#getContents--}
```
public InputStream getContents()
```


Получает поток звука, который будет воспроизводиться при активации аннотации.

**Возвращает:**
java.io.InputStream — значение InputStream
### getContentsInternal() {#getContentsInternal--}
```
public System.IO.Stream getContentsInternal()
```


Получает поток звука, который будет воспроизводиться при активации аннотации.

**Возвращает:**
com.aspose.ms.System.IO.Stream — значение потока
### getEncoding() {#getEncoding--}
```
public int getEncoding()
```


Получает формат кодировки для примера данных.

**Возвращает:**
int — значение SoundEncoding
### getRate() {#getRate--}
```
public int getRate()
```


Получает частоту дискретизации в выборках в секунду.

**Возвращает:**
интервал - целочисленное значение
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




### setBits(int value) {#setBits-int-}
```
public void setBits(int value)
```


Устанавливает количество битов на значение выборки на канал.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | количество бит |

### setChannels(int value) {#setChannels-int-}
```
public void setChannels(int value)
```


Устанавливает количество звуковых каналов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Количество звуковых каналов. |

### setEncoding(int value) {#setEncoding-int-}
```
public void setEncoding(int value)
```


Устанавливает формат кодирования для демонстрационных данных.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение SoundEncoding |

### setRate(int value) {#setRate-int-}
```
public void setRate(int value)
```


Устанавливает частоту дискретизации в выборках в секунду.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

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
