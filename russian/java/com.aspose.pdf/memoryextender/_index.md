---
title: MemoryExtender
second_title: Aspose.PDF для справки по Java API
description: Представляет класс MemoryExtender При использовании больших файлов в системе с ограниченной памятью кучи можно включить использование дискового пространства в качестве временной памяти подкачки.
type: docs
weight: 218
url: /ru/java/com.aspose.pdf/memoryextender/
---
**Наследование:**
java.lang.Object
```
public class MemoryExtender
```

Представляет класс MemoryExtender. При использовании больших файлов в системе с ограниченной памятью кучи можно включить использование дискового пространства в качестве временной памяти подкачки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MemoryExtender()](#MemoryExtender--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCallBackPageImage()](#getCallBackPageImage--) | Получите пользовательский анализатор кеша. |
| [getClass()](#getClass--) |  |
| [getElementRenderingTimeout()](#getElementRenderingTimeout--) | Максимальное время рендеринга одного элемента, используемого при преобразовании страницы в изображение. |
| [hashCode()](#hashCode--) |  |
| [isEnabledMultiPageImageCache()](#isEnabledMultiPageImageCache--) | Получить статус для поля EnabledMultiPageImageCache |
| [isOptimizedMemoryStreamByDefault()](#isOptimizedMemoryStreamByDefault--) | Включено использование OptimizedMemoryStream в качестве хранилища памяти по умолчанию. |
| [isOptimizedMemoryStreamByDefault(boolean value)](#isOptimizedMemoryStreamByDefault-boolean-) | Включено использование OptimizedMemoryStream в качестве хранилища памяти по умолчанию. |
| [isSkipHeavyContentEnabled()](#isSkipHeavyContentEnabled--) | Включен пропуск объектов с высоким потреблением памяти при рендеринге с недостатком памяти в куче. |
| [isSwapEnabled()](#isSwapEnabled--) | Включено использование дискового пространства в качестве временной памяти подкачки. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_)](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Примените новый пользовательский анализатор кеша. |
| [setElementRenderingTimeout(int value)](#setElementRenderingTimeout-int-) | Максимальное время рендеринга одного элемента, используемого при преобразовании страницы в изображение. |
| [setEnableMultiPageCache(boolean enableMultiPageImageCache_)](#setEnableMultiPageCache-boolean-) | Установите новый статус для поля EnabledMultiPageImageCache. |
| [setSkipHeavyContentEnabled(boolean value)](#setSkipHeavyContentEnabled-boolean-) | Установите флаг, чтобы разрешить пропускать объекты с высоким потреблением памяти при рендеринге с недостатком памяти в куче. |
| [setSwapEnabled(boolean value)](#setSwapEnabled-boolean-) | Установите флаг, разрешено ли использование дискового пространства в качестве временной памяти подкачки. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MemoryExtender() {#MemoryExtender--}
```
public MemoryExtender()
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
### getCallBackPageImage() {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```


Получите пользовательский анализатор кеша.

**Возвращает:**
[CallBackPageImage](../../com.aspose.pdf/callbackpageimage) - Объект CallBackPageImage
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getElementRenderingTimeout() {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```


Максимальное время рендеринга одного элемента, используемого при преобразовании страницы в изображение. Значение по умолчанию 10000 миллисекунд. Используется только когда isSkipHeavyContentEnabled() == true

**Возвращает:**
int - значение int Количество миллисекунд
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isEnabledMultiPageImageCache() {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```


Получить статус для поля EnabledMultiPageImageCache

**Возвращает:**
boolean - логическое значение
### isOptimizedMemoryStreamByDefault() {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```


Включено использование OptimizedMemoryStream в качестве хранилища памяти по умолчанию. Требуется для работы с большими документами более 2 Гб. Значение по умолчанию — ЛОЖЬ.

**Возвращает:**
boolean - логическое значение
### isOptimizedMemoryStreamByDefault(boolean value) {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```


Включено использование OptimizedMemoryStream в качестве хранилища памяти по умолчанию. Требуется для работы с большими документами более 2 Гб. Значение по умолчанию — ЛОЖЬ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### isSkipHeavyContentEnabled() {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```


Включен пропуск объектов с высоким потреблением памяти при рендеринге с недостатком памяти в куче. Значение по умолчанию — ЛОЖЬ.

**Возвращает:**
boolean - логическое значение
### isSwapEnabled() {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```


Включено использование дискового пространства в качестве временной памяти подкачки. Значение по умолчанию — ЛОЖЬ.

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




### setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_) {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
```
public static void setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_)
```


Примените новый пользовательский анализатор кеша.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| callBackPageImage_ | [CallBackPageImage](../../com.aspose.pdf/callbackpageimage) | Объект CallBackPageImage |

### setElementRenderingTimeout(int value) {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```


Максимальное время рендеринга одного элемента, используемого при преобразовании страницы в изображение. Значение по умолчанию 10000 миллисекунд. Используется только в том случае, если isSkipHeavyContentEnabled() == true

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | int value Количество миллисекунд |

### setEnableMultiPageCache(boolean enableMultiPageImageCache_) {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```


Установите новый статус для поля EnabledMultiPageImageCache.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| enableMultiPageImageCache_ | логический | логическое значение |

### setSkipHeavyContentEnabled(boolean value) {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```


Установите флаг, чтобы разрешить пропускать объекты с высоким потреблением памяти при рендеринге с недостатком памяти в куче.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSwapEnabled(boolean value) {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```


Установите флаг, разрешено ли использование дискового пространства в качестве временной памяти подкачки.

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
