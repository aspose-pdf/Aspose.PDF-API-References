---
title: ExplicitDestination
second_title: Aspose.PDF для справки по Java API
description: Представляет базовый класс для явных назначений в документе PDF.
type: docs
weight: 102
url: /ru/java/com.aspose.pdf/explicitdestination/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.pdf.IAppointment](../../com.aspose.pdf/iappointment)
```
public abstract class ExplicitDestination implements IAppointment
```

Представляет базовый класс для явных назначений в документе PDF.
## Методы

| Метод | Описание |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | Создает экземпляр классов-потомков ExplicitDestination. |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPage()](#getPage--) | Получает объект целевой страницы |
| [getPageNumber()](#getPageNumber--) | Получает номер целевой страницы |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает строковое представление объекта ExplicitDestination. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createDestination(IDocument doc, int pageNumber, int type, double[] values) {#createDestination-com.aspose.pdf.IDocument-int-int-double...-}
```
public static ExplicitDestination createDestination(IDocument doc, int pageNumber, int type, double[] values)
```


Создает экземпляры классов-потомков ExplicitDestination.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Документ, в котором будет создан пункт назначения. |
| pageNumber | int | Номер страницы. |
| type | int | Тип назначения. |
| values | double[] | Массив конкретных значений назначения. |

**Возвращает:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - Явный целевой объект.
### createDestination(Page page, int type, double[] values) {#createDestination-com.aspose.pdf.Page-int-double...-}
```
public static ExplicitDestination createDestination(Page page, int type, double[] values)
```


Создает экземпляры классов-потомков ExplicitDestination.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект целевой страницы. |
| type | int | Тип явного назначения. |
| values | double[] | Массив двойных значений. |

**Возвращает:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - Явный целевой объект.
### createDestination(IPdfArray engineDest) {#createDestination-com.aspose.pdf.engine.data.IPdfArray-}
```
public static ExplicitDestination createDestination(IPdfArray engineDest)
```


Создает экземпляр классов-потомков ExplicitDestination.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| engineDest | [IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray) | Целевой объект двигателя. |

**Возвращает:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - Явный целевой объект DOM.
### createDestination(int pageNumber, int type, double[] values) {#createDestination-int-int-double...-}
```
public static ExplicitDestination createDestination(int pageNumber, int type, double[] values)
```


Создает экземпляры классов-потомков ExplicitDestination.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер целевой страницы. |
| type | int | Тип явного назначения. |
| values | double[] | Массив двойных значений. |

**Возвращает:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - Явный целевой объект.
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
### getPage() {#getPage--}
```
public Page getPage()
```


Получает объект целевой страницы

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Объект страницы
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Получает номер целевой страницы

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




### toString() {#toString--}
```
public abstract String toString()
```


Возвращает строковое представление объекта ExplicitDestination.

**Возвращает:**
java.lang.String — строковое представление
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
