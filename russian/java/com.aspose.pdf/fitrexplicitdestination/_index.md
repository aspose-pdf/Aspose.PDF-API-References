---
title: FitRExplicitDestination
second_title: Aspose.PDF для справки по Java API
description: Представляет явный пункт назначения, который отображает страницу с ее содержимым, увеличенным настолько, чтобы соответствовать прямоугольнику, заданному координатами слева внизу справа и в углу окна как по горизонтали, так и по вертикали.
type: docs
weight: 124
url: /ru/java/com.aspose.pdf/fitrexplicitdestination/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitRExplicitDestination extends ExplicitDestination
```

Представляет явное место назначения, которое отображает страницу с ее содержимым, увеличенным настолько, чтобы соответствовать прямоугольнику, заданному координатами слева, снизу, справа и вверху внутри окна как по горизонтали, так и по вертикали. Если требуемые коэффициенты увеличения по горизонтали и вертикали различаются, используйте меньший из двух, центрируя прямоугольник внутри окна в другом измерении. Нулевое значение любого из параметров может привести к непредсказуемому поведению.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FitRExplicitDestination(Page page, double left, double bottom, double right, double top)](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Создает экземпляр и инициализирует его с помощью объекта страницы DOM и видимых параметров. |
| [FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top)](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Создает удаленный явный пункт назначения. |
| [FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)](#FitRExplicitDestination-int-double-double-double-double-) | Создает удаленный явный пункт назначения. |
## Методы

| Метод | Описание |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | Создает экземпляр классов-потомков ExplicitDestination. |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Получает нижнюю вертикальную координату видимого прямоугольника. |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | Получает левую горизонтальную координату видимого прямоугольника. |
| [getPage()](#getPage--) | Получает объект целевой страницы |
| [getPageNumber()](#getPageNumber--) | Получает номер целевой страницы |
| [getRight()](#getRight--) | Получает правую горизонтальную координату видимого прямоугольника. |
| [getTop()](#getTop--) | Получает верхнюю вертикальную координату видимого прямоугольника. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Преобразует состояние объекта в строковое значение. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FitRExplicitDestination(Page page, double left, double bottom, double right, double top) {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
```
public FitRExplicitDestination(Page page, double left, double bottom, double right, double top)
```


Создает экземпляр и инициализирует его с помощью объекта страницы DOM и видимых параметров.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы DOM. |
| left | double | Левая горизонтальная координата видимого прямоугольника. |
| bottom | double | Нижняя вертикальная координата видимого прямоугольника. |
| right | double | Правая горизонтальная координата видимого прямоугольника. |
| top | double | Верхняя вертикальная координата видимого прямоугольника. |

### FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top) {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
```
public FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | Родительский документ, содержащий этот объект. |
| pageNumber | int | Номер целевой страницы удаленного документа. |
| left | double | Левая горизонтальная координата видимого прямоугольника. |
| bottom | double | Нижняя вертикальная координата видимого прямоугольника. |
| right | double | Правая горизонтальная координата видимого прямоугольника. |
| top | double | Верхняя вертикальная координата видимого прямоугольника. |

### FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top) {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер целевой страницы удаленного документа. |
| left | double | Левая горизонтальная координата видимого прямоугольника. |
| bottom | double | Нижняя вертикальная координата видимого прямоугольника. |
| right | double | Правая горизонтальная координата видимого прямоугольника. |
| top | double | Верхняя вертикальная координата видимого прямоугольника. |

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
### getBottom() {#getBottom--}
```
public double getBottom()
```


Получает нижнюю вертикальную координату видимого прямоугольника.

**Возвращает:**
двойное - двойное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getLeft() {#getLeft--}
```
public double getLeft()
```


Получает левую горизонтальную координату видимого прямоугольника.

**Возвращает:**
двойное - двойное значение
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
### getRight() {#getRight--}
```
public double getRight()
```


Получает правую горизонтальную координату видимого прямоугольника.

**Возвращает:**
двойное - двойное значение
### getTop() {#getTop--}
```
public double getTop()
```


Получает верхнюю вертикальную координату видимого прямоугольника.

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


Преобразует состояние объекта в строковое значение. Пример: «1 FitR 100 200 300 400».

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
