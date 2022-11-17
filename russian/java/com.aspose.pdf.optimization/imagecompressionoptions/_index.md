---
title: ImageCompressionOptions
second_title: Aspose.PDF для справки по Java API
description: Класс содержит заданные параметры сжатия изображений.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Наследование:**
java.lang.Object
```
public class ImageCompressionOptions
```

Класс содержит заданные параметры сжатия изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageCompressionOptions()](#ImageCompressionOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Получает или задает кодировку, используемую для хранения изображений. |
| [getImageQuality()](#getImageQuality--) | Указывает уровень сжатия изображения при использовании флага CompressIamges. |
| [getMaxResolution()](#getMaxResolution--) | Задает максимальное разрешение изображений. |
| [getResizeImages()](#getResizeImages--) | Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution. |
| [getVersion()](#getVersion--) | Версия алгоритма сжатия. |
| [hashCode()](#hashCode--) |  |
| [isCompressImages()](#isCompressImages--) | Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality. |
| [setEncoding(int value)](#setEncoding-int-) | Получает или задает кодировку, используемую для хранения изображений. |
| [setImageQuality(int value)](#setImageQuality-int-) | Указывает уровень сжатия изображения при использовании флага CompressIamges. |
| [setMaxResolution(int value)](#setMaxResolution-int-) | Задает максимальное разрешение изображений. |
| [setResizeImages(boolean value)](#setResizeImages-boolean-) | Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution. |
| [setVersion(int value)](#setVersion-int-) | Версия алгоритма сжатия. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageCompressionOptions() {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEncoding() {#getEncoding--}
```
public final int getEncoding()
```


Получает или задает кодировку, используемую для хранения изображений.

**Возвращает:**
int — элемент ImageEncoding
### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Указывает уровень сжатия изображения при использовании флага CompressIamges.

**Возвращает:**
интервал - целочисленное значение
### getMaxResolution() {#getMaxResolution--}
```
public final int getMaxResolution()
```


Задает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано.

**Возвращает:**
интервал - целочисленное значение
### getResizeImages() {#getResizeImages--}
```
public final boolean getResizeImages()
```


Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution.

**Возвращает:**
boolean - логическое значение
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее стандартного, но может быть применимо не ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые не могут быть сжаты более быстрым алгоритмом, это может дать наилучшее сжатие, но более медленное, чем "быстрый" алгоритм. Версия "Быстрый" не применима для изменения размера изображений (будет использоваться стандартный метод). По умолчанию "Стандартный".

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCompressImages() {#isCompressImages--}
```
public final boolean isCompressImages()
```


Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setEncoding(int value) {#setEncoding-int-}
```
public final void setEncoding(int value)
```


Получает или задает кодировку, используемую для хранения изображений.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ImageEncoding |

### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Указывает уровень сжатия изображения при использовании флага CompressIamges.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setMaxResolution(int value) {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```


Задает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setResizeImages(boolean value) {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```


Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее стандартного, но может быть применимо не ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые не могут быть сжаты более быстрым алгоритмом, это может дать наилучшее сжатие, но более медленное, чем "быстрый" алгоритм. Версия "Быстрый" не применима для изменения размера изображений (будет использоваться стандартный метод). По умолчанию "Стандартный".

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
