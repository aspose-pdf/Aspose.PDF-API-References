---
title: XfaParserOptions
second_title: Aspose.PDF для справки по Java API
description: класс для обработки связанной инкапсуляции данных
type: docs
weight: 412
url: /ru/java/com.aspose.pdf/xfaparseroptions/
---
**Наследование:**
java.lang.Object
```
public class XfaParserOptions
```

класс для обработки связанной инкапсуляции данных
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XfaParserOptions(Dimension2D pageSize)](#XfaParserOptions-java.awt.geom.Dimension2D-) | Инициализирует новый экземпляр класса XfaParserOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | Получает или задает базовый путь. |
| [getClass()](#getClass--) |  |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | Если это свойство истинно, то для требуемых Xfa "исключенных групп" будут нарисованы дополнительные красные прямоугольники. Это свойство было введено из-за отсутствия аналогий исключаемых групп при преобразовании Xfa представления форм к стандартному. |
| [getPageSize()](#getPageSize--) | Получает или задает размер страницы. |
| [getSigned()](#getSigned--) | Если это свойство истинно, то документ будет конвертирован с использованием потока форм xfa (если он существует). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasePath(URI value)](#setBasePath-java.net.URI-) | Получает или задает базовый путь. |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | Если это свойство истинно, то для требуемых Xfa "исключенных групп" будут нарисованы дополнительные красные прямоугольники. Это свойство было введено из-за отсутствия аналогий исключаемых групп при преобразовании Xfa представления форм к стандартному. |
| [setPageSize(Dimension2D value)](#setPageSize-java.awt.geom.Dimension2D-) | Получает или задает размер страницы. |
| [setSigned(boolean value)](#setSigned-boolean-) | Если это свойство истинно, то документ будет конвертирован с использованием потока форм xfa (если он существует). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XfaParserOptions(Dimension2D pageSize) {#XfaParserOptions-java.awt.geom.Dimension2D-}
```
public XfaParserOptions(Dimension2D pageSize)
```


Инициализирует новый экземпляр класса XfaParserOptions.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | Размер страницы. |

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
### getBasePath() {#getBasePath--}
```
public URI getBasePath()
```


Получает или задает базовый путь.

Значение: базовый путь.

**Возвращает:**
java.net.URI — объект URI
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


Если это свойство истинно, то для требуемых Xfa "исключенных групп" будут нарисованы дополнительные красные прямоугольники. Это свойство было введено из-за отсутствия аналогий исключаемых групп при преобразовании Xfa представления форм к стандартному. По умолчанию это ложь.

**Возвращает:**
boolean - логическое значение
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Получает или задает размер страницы.

Значение: Размер страницы.

**Возвращает:**
java.awt.geom.Dimension2D — объект Dimension2D
### getSigned() {#getSigned--}
```
public boolean getSigned()
```


Если это свойство истинно, то документ будет конвертирован с использованием потока форм xfa (если он существует). Если оно ложно, то поток формы xfa будет проигнорирован. Это свойство введено из-за того, что непонятно, как считать контрольную сумму, используемую для проверки сигнатуры.

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




### setBasePath(URI value) {#setBasePath-java.net.URI-}
```
public void setBasePath(URI value)
```


Получает или задает базовый путь.

Значение: базовый путь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.net.URI | URI-объект |

### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


Если это свойство истинно, то для требуемых Xfa "исключенных групп" будут нарисованы дополнительные красные прямоугольники. Это свойство было введено из-за отсутствия аналогий исключаемых групп при преобразовании Xfa представления форм к стандартному. По умолчанию это ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPageSize(Dimension2D value) {#setPageSize-java.awt.geom.Dimension2D-}
```
public void setPageSize(Dimension2D value)
```


Получает или задает размер страницы.

Значение: Размер страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D | Объект Dimension2D |

### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


Если это свойство истинно, то документ будет конвертирован с использованием потока форм xfa (если он существует). Если оно ложно, то поток формы xfa будет проигнорирован. Это свойство введено из-за того, что непонятно, как считать контрольную сумму, используемую для проверки сигнатуры.

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
