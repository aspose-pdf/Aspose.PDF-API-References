---
title: FitBHExplicitDestination
second_title: Aspose.PDF для справки по Java API
description: Представляет явное место назначения, которое отображает страницу с вертикальной координатой, расположенной у верхнего края окна, и содержимое страницы увеличивается настолько, чтобы соответствовать всей ширине ее ограничивающей рамки в окне.
type: docs
weight: 120
url: /ru/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Представляет явное место назначения, которое отображает страницу с вертикальной координатой top, расположенной на верхнем краю окна, и содержимое страницы, увеличенное настолько, чтобы соответствовать всей ширине ее ограничивающей рамки в окне. Нулевое значение для top указывает, что текущее значение этого параметра должно быть сохранено без изменений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FitBHExplicitDestination(Page page, double top)](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Создает экземпляр и инициализирует его с помощью объекта страницы DOM и параметра top. |
| [FitBHExplicitDestination(Document document, int pageNumber, double top)](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Создает удаленный явный пункт назначения. |
| [FitBHExplicitDestination(int pageNumber, double top)](#FitBHExplicitDestination-int-double-) | Создает удаленный явный пункт назначения. |
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
| [getTop()](#getTop--) | Получает вертикальную координату сверху, расположенную на верхнем краю окна. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Преобразует состояние объекта в строковое значение. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FitBHExplicitDestination(Page page, double top) {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
```
public FitBHExplicitDestination(Page page, double top)
```


Создает экземпляр и инициализирует его с помощью объекта страницы DOM и параметра top.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы DOM. |
| top | double | Вертикальная координата top расположена на верхнем краю окна. |

### FitBHExplicitDestination(Document document, int pageNumber, double top) {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
```
public FitBHExplicitDestination(Document document, int pageNumber, double top)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | Родительский документ, содержащий этот объект. |
| pageNumber | int | Номер целевой страницы удаленного документа. |
| top | double | Вертикальная координата top расположена на верхнем краю окна. |

### FitBHExplicitDestination(int pageNumber, double top) {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер целевой страницы удаленного документа. |
| top | double | Вертикальная координата top расположена на верхнем краю окна. |

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
### getTop() {#getTop--}
```
public double getTop()
```


Получает вертикальную координату сверху, расположенную на верхнем краю окна.

**Возвращает:**
двойное - двойное значение
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


Преобразует состояние объекта в строковое значение. Пример: «1 FitBH 100».

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
