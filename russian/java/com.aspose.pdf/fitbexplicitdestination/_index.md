---
title: FitBExplicitDestination
second_title: Aspose.PDF для справки по Java API
description: Представляет явный пункт назначения, который отображает страницу с увеличенным содержимым настолько, чтобы ограничивающая рамка полностью помещалась в окне как по горизонтали, так и по вертикали.
type: docs
weight: 119
url: /ru/java/com.aspose.pdf/fitbexplicitdestination/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitBExplicitDestination extends ExplicitDestination
```

Представляет явный пункт назначения, который отображает страницу с увеличенным содержимым настолько, чтобы ограничивающая рамка полностью помещалась в окне как по горизонтали, так и по вертикали. Если требуемые коэффициенты увеличения по горизонтали и вертикали различаются, используйте меньший из двух, центрируя ограничивающую рамку внутри окна в другом измерении.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FitBExplicitDestination(Page page)](#FitBExplicitDestination-com.aspose.pdf.Page-) | Создает экземпляр и инициализирует его объектом страницы DOM. |
| [FitBExplicitDestination(Document document, int pageNumber)](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | Создает удаленный явный пункт назначения. |
| [FitBExplicitDestination(int pageNumber)](#FitBExplicitDestination-int-) | Создает удаленный явный пункт назначения. |
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
| [toString()](#toString--) | Преобразует состояние объекта в строковое значение. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FitBExplicitDestination(Page page) {#FitBExplicitDestination-com.aspose.pdf.Page-}
```
public FitBExplicitDestination(Page page)
```


Создает экземпляр и инициализирует его объектом страницы DOM.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы DOM. |

### FitBExplicitDestination(Document document, int pageNumber) {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
```
public FitBExplicitDestination(Document document, int pageNumber)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | Родительский документ, содержащий этот объект. |
| pageNumber | int | Номер целевой страницы удаленного документа. |

### FitBExplicitDestination(int pageNumber) {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер целевой страницы удаленного документа. |

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
public String toString()
```


Преобразует состояние объекта в строковое значение. Пример: «1 FitB».

**Возвращает:**
java.lang.String — строковое значение, представляющее состояние объекта.
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
