---
title: Document.OptimizationOptions
second_title: Aspose.PDF для справки по Java API
description: Класс, описывающий алгоритм оптимизации документа.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf/document.optimizationoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.optimization.OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions)
```
public static class Document.OptimizationOptions extends OptimizationOptions
```

Класс, описывающий алгоритм оптимизации документа. Экземпляр этого класса может использоваться как параметр метода OptimizeResources().
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OptimizationOptions()](#OptimizationOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [all()](#all--) | Создает стратегию оптимизации, активируя все опции. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | Если истинно, содержимое страницы будет использоваться повторно, когда документ оптимизируется для одинаковых страниц. |
| [getClass()](#getClass--) |  |
| [getCompressImages()](#getCompressImages--) | Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality. |
| [getImageCompressionOptions()](#getImageCompressionOptions--) | Набор опций, описывающих будут ли сжиматься изображения в документе и параметры сжатия. |
| [getImageEncoding()](#getImageEncoding--) | Кодировщик изображения, который будет использоваться. |
| [getImageQuality()](#getImageQuality--) | Указывает уровень сжатия изображения при использовании флага CompressIamges. |
| [getLinkDuplcateStreams()](#getLinkDuplcateStreams--) | Если для этого флага установлено значение true, будут проанализированы потоки ресурсов. |
| [getMaxResoultion()](#getMaxResoultion--) | Задает максимальное разрешение изображений. |
| [getMaximumImageDimension()](#getMaximumImageDimension--) | Задает максимальный размер изображения. |
| [getRemovePrivateInfo()](#getRemovePrivateInfo--) | Удалить личную информацию (информация о части страницы). |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Если этот флаг установлен в значение true, все объекты документа будут проверены, а неиспользуемые объекты (т.е. объекты, на которые нет ссылок) будут удалены из документа. |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Если для этого флага установлено значение true, каждый ресурс проверяется на его использование. |
| [getResizeImages()](#getResizeImages--) | Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution. |
| [getResolution()](#getResolution--) | Указывает новое разрешение изображения при использовании флага CompressIamges. |
| [getSubsetFonts()](#getSubsetFonts--) | Шрифты будут преобразованы в подмножества, если установлено значение true. |
| [getUnembedFonts()](#getUnembedFonts--) | Сделать шрифты не встроенными, если установлено значение true. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | Если истинно, содержимое страницы будет использоваться повторно, когда документ оптимизируется для одинаковых страниц. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality. |
| [setImageEncoding(int value)](#setImageEncoding-int-) | Кодировщик изображения, который будет использоваться. |
| [setImageQuality(int value)](#setImageQuality-int-) | Указывает уровень сжатия изображения при использовании флага CompressIamges. |
| [setLinkDuplcateStreams(boolean value)](#setLinkDuplcateStreams-boolean-) | Если для этого флага установлено значение true, будут проанализированы потоки ресурсов. |
| [setMaxResoultion(int value)](#setMaxResoultion-int-) | Задает максимальное разрешение изображений. |
| [setMaximumImageDimension(int dimension)](#setMaximumImageDimension-int-) | Задает максимальный размер изображения. |
| [setRemovePrivateInfo(boolean value)](#setRemovePrivateInfo-boolean-) | Удалить личную информацию (информация о части страницы). |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Если этот флаг установлен в значение true, все объекты документа будут проверены, а неиспользуемые объекты (т.е. объекты, на которые нет ссылок) будут удалены из документа. |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Если для этого флага установлено значение true, каждый ресурс проверяется на его использование. |
| [setResizeImages(boolean value)](#setResizeImages-boolean-) | Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution. |
| [setResolution(int dpi)](#setResolution-int-) | Указывает новое разрешение изображения при использовании флага CompressIamges. |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | Шрифты будут преобразованы в подмножества, если установлено значение true. |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Сделать шрифты не встроенными, если установлено значение true. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptimizationOptions() {#OptimizationOptions--}
```
public OptimizationOptions()
```


### all() {#all--}
```
public static Document.OptimizationOptions all()
```


Создает стратегию оптимизации, активируя все опции.

**Возвращает:**
[OptimizationOptions](../../com.aspose.pdf/optimizationoptions) - Объект OptimizationOptions.
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
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public final boolean getAllowReusePageContent()
```


Если истинно, содержимое страницы будет использоваться повторно, когда документ оптимизируется для одинаковых страниц.

**Возвращает:**
boolean - логическое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality.

**Возвращает:**
boolean - логическое значение
### getImageCompressionOptions() {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```


Набор опций, описывающих будут ли сжиматься изображения в документе и параметры сжатия.

**Возвращает:**
[ImageCompressionOptions](../../com.aspose.pdf.optimization/imagecompressionoptions) - Экземпляр ImageCompressionOptions
### getImageEncoding() {#getImageEncoding--}
```
public final int getImageEncoding()
```


Кодировщик изображения, который будет использоваться.

**Возвращает:**
int — элемент ImageEncoding
### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Указывает уровень сжатия изображения при использовании флага CompressIamges.

**Возвращает:**
интервал - целочисленное значение
### getLinkDuplcateStreams() {#getLinkDuplcateStreams--}
```
public final boolean getLinkDuplcateStreams()
```


Если для этого флага установлено значение true, будут проанализированы потоки ресурсов. Если обнаружены повторяющиеся потоки (т. е. если содержимое потоков одинаково), то эти потоки будут сохранены как один объект. Это позволяет в некоторых случаях уменьшить размер документа (например, когда один и тот же документ был объединен несколько раз).

**Возвращает:**
boolean - логическое значение
### getMaxResoultion() {#getMaxResoultion--}
```
public final int getMaxResoultion()
```


Задает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано.

**Возвращает:**
интервал - целочисленное значение
### getMaximumImageDimension() {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```


Задает максимальный размер изображения. Если ширина изображения или высота существующего изображения больше этого значения - размер изображения будет пропорционально уменьшен.

**Возвращает:**
int - максимальный размер изображения
### getRemovePrivateInfo() {#getRemovePrivateInfo--}
```
public final boolean getRemovePrivateInfo()
```


Удалить личную информацию (информация о части страницы).

**Возвращает:**
boolean - логическое значение
### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Если этот флаг установлен в значение true, все объекты документа будут проверены, а неиспользуемые объекты (т.е. объекты, на которые нет ссылок) будут удалены из документа.

**Возвращает:**
boolean - логическое значение
### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Если для этого флага установлено значение true, каждый ресурс проверяется на его использование. Если ресурс никогда не используется, то ресурсы удаляются. Это может уменьшить размер документа, например, когда страницы были извлечены из документа.

**Возвращает:**
boolean - логическое значение
### getResizeImages() {#getResizeImages--}
```
public final boolean getResizeImages()
```


Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution.

**Возвращает:**
boolean - логическое значение
### getResolution() {#getResolution--}
```
public int getResolution()
```


Указывает новое разрешение изображения при использовании флага CompressIamges.

**Возвращает:**
int - разрешение изображения
### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


Шрифты будут преобразованы в подмножества, если установлено значение true.

**Возвращает:**
boolean - логическое значение
### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Сделать шрифты не встроенными, если установлено значение true.

**Возвращает:**
boolean - логическое значение
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




### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```


Если истинно, содержимое страницы будет использоваться повторно, когда документ оптимизируется для одинаковых страниц.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setImageEncoding(int value) {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```


Кодировщик изображения, который будет использоваться.

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

### setLinkDuplcateStreams(boolean value) {#setLinkDuplcateStreams-boolean-}
```
public final void setLinkDuplcateStreams(boolean value)
```


Если для этого флага установлено значение true, будут проанализированы потоки ресурсов. Если обнаружены повторяющиеся потоки (т. е. если содержимое потоков одинаково), то эти потоки будут сохранены как один объект. Это позволяет в некоторых случаях уменьшить размер документа (например, когда один и тот же документ был объединен несколько раз).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMaxResoultion(int value) {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```


Задает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setMaximumImageDimension(int dimension) {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```


Задает максимальный размер изображения. Если ширина изображения или высота существующего изображения больше этого значения - размер изображения будет пропорционально уменьшен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| dimension | int | максимальный размер изображения |

### setRemovePrivateInfo(boolean value) {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```


Удалить личную информацию (информация о части страницы).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Если этот флаг установлен в значение true, все объекты документа будут проверены, а неиспользуемые объекты (т.е. объекты, на которые нет ссылок) будут удалены из документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Если для этого флага установлено значение true, каждый ресурс проверяется на его использование. Если ресурс никогда не используется, то ресурсы удаляются. Это может уменьшить размер документа, например, когда страницы были извлечены из документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setResizeImages(boolean value) {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```


Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setResolution(int dpi) {#setResolution-int-}
```
public void setResolution(int dpi)
```


Указывает новое разрешение изображения при использовании флага CompressIamges.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| dpi | int | Разрешение изображения |

### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


Шрифты будут преобразованы в подмножества, если установлено значение true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Сделать шрифты не встроенными, если установлено значение true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
