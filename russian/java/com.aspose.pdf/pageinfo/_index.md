---
title: PageInfo
second_title: Aspose.PDF для справки по Java API
description: Представляет информацию о странице для генератора PDF.
type: docs
weight: 261
url: /ru/java/com.aspose.pdf/pageinfo/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.ICloneable
```
public class PageInfo implements System.ICloneable
```

Представляет информацию о странице для генератора PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageInfo()](#PageInfo--) | конструктор по умолчанию |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонировать информацию о странице. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnyMargin()](#getAnyMargin--) | Получает или задает поля для любой страницы, кроме первой. |
| [getClass()](#getClass--) |  |
| [getDefaultTextState()](#getDefaultTextState--) | Получает шрифт по умолчанию. |
| [getHeight()](#getHeight--) | Получает высоту страницы. |
| [getMargin()](#getMargin--) | Получает поля страницы. |
| [getPureHeight()](#getPureHeight--) | Получает чистую высоту страницы без полей. |
| [getWidth()](#getWidth--) | Получает ширину страницы. |
| [hashCode()](#hashCode--) |  |
| [isLandscape()](#isLandscape--) | Получает ландшафтную страницу. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAnyMargin(MarginInfo value)](#setAnyMargin-com.aspose.pdf.MarginInfo-) | Получает или задает поля для любой страницы, кроме первой. |
| [setDefaultTextState(TextState value)](#setDefaultTextState-com.aspose.pdf.TextState-) | Устанавливает шрифт по умолчанию. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает высоту страницы. |
| [setLandscape(boolean value)](#setLandscape-boolean-) | Наборы - это страница с ландшафтным дизайном. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает поля страницы. |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину страницы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PageInfo() {#PageInfo--}
```
public PageInfo()
```


конструктор по умолчанию

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонировать информацию о странице.

**Возвращает:**
java.lang.Object — клонированный объект
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
### getAnyMargin() {#getAnyMargin--}
```
public final MarginInfo getAnyMargin()
```


Получает или задает поля для любой страницы, кроме первой.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Экземпляр MarginInfo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDefaultTextState() {#getDefaultTextState--}
```
public TextState getDefaultTextState()
```


Получает шрифт по умолчанию.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Экземпляр TextState
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает высоту страницы.

**Возвращает:**
двойное - двойное значение
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает поля страницы.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getPureHeight() {#getPureHeight--}
```
public double getPureHeight()
```


Получает чистую высоту страницы без полей.

**Возвращает:**
двойное - двойное значение
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает ширину страницы.

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Получает ландшафтную страницу.

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




### setAnyMargin(MarginInfo value) {#setAnyMargin-com.aspose.pdf.MarginInfo-}
```
public final void setAnyMargin(MarginInfo value)
```


Получает или задает поля для любой страницы, кроме первой.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Экземпляр MarginInfo |

### setDefaultTextState(TextState value) {#setDefaultTextState-com.aspose.pdf.TextState-}
```
public void setDefaultTextState(TextState value)
```


Устанавливает шрифт по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Экземпляр TextState |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Устанавливает высоту страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setLandscape(boolean value) {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```


Наборы - это страница с ландшафтным дизайном.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает поля страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Значение MarginInfo |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает ширину страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

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
