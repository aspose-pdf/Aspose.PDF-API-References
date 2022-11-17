---
title: XYZExplicitDestination
second_title: Aspose.PDF для справки по Java API
description: Представляет явное место назначения, которое отображает страницу с координатами слева вверху в левом верхнем углу окна, а содержимое страницы увеличивается с коэффициентом масштабирования.
type: docs
weight: 411
url: /ru/java/com.aspose.pdf/xyzexplicitdestination/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class XYZExplicitDestination extends ExplicitDestination
```

Представляет явный пункт назначения, отображающий страницу с координатами (слева, сверху), расположенными в верхнем левом углу окна, и содержимым страницы, увеличенным с помощью коэффициента масштабирования. Нулевое значение для любого из параметров left, top или zoom указывает, что текущее значение этого параметра должно быть сохранено без изменений. Значение масштабирования 0 имеет то же значение, что и нулевое значение.

--------------------

Документ doc = новый документ ("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get\_Item(1).getDestination(); Строка слева = dest.getLeft(); Верх строки = dest.getTop(); Строка zoom = dest.getZoom();
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XYZExplicitDestination(Page page, double left, double top, double zoom)](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Создает экземпляр и инициализирует его с помощью объекта страницы DOM и видимых параметров. |
| [XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom)](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Создает удаленный явный пункт назначения. |
| [XYZExplicitDestination(int pageNumber, double left, double top, double zoom)](#XYZExplicitDestination-int-double-double-double-) | Создает удаленный явный пункт назначения. |
## Методы

| Метод | Описание |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [createDestination(Page page, double left, double top, double zoom, boolean considerRotation)](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Создайте место назначения в указанном месте страницы с учетом поворота страницы, если это необходимо. |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | Создает экземпляр классов-потомков ExplicitDestination. |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Создает экземпляры классов-потомков ExplicitDestination. |
| [createDestinationToUpperLeftCorner(Page page)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Создать назначение на указанную страницу. |
| [createDestinationToUpperLeftCorner(Page page, double zoom)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Создать пункт назначения в верхнем левом углу указанной страницы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | Получает левую горизонтальную координату левого верхнего угла окна. |
| [getPage()](#getPage--) | Получает объект целевой страницы |
| [getPageNumber()](#getPageNumber--) | Получает номер целевой страницы |
| [getTop()](#getTop--) | Получает верхнюю вертикальную координату левого верхнего угла окна. |
| [getZoom()](#getZoom--) | Получает коэффициент масштабирования. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Преобразует состояние объекта в строковое значение. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XYZExplicitDestination(Page page, double left, double top, double zoom) {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
```
public XYZExplicitDestination(Page page, double left, double top, double zoom)
```


Создает экземпляр и инициализирует его с помощью объекта страницы DOM и видимых параметров.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы DOM. |
| left | double | Левая горизонтальная координата левого верхнего угла окна. |
| top | double | Верхняя вертикальная координата левого верхнего угла окна. |
| zoom | double | Коэффициент масштабирования. |

### XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom) {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
```
public XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Родительский документ, содержащий этот объект. |
| pageNumber | int | Номер целевой страницы удаленного документа. |
| left | double | Левая горизонтальная координата левого верхнего угла окна. |
| top | double | Верхняя вертикальная координата левого верхнего угла окна. |
| zoom | double | Коэффициент масштабирования. |

### XYZExplicitDestination(int pageNumber, double left, double top, double zoom) {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```


Создает удаленный явный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер целевой страницы удаленного документа. |
| left | double | Левая горизонтальная координата левого верхнего угла окна. |
| top | double | Верхняя вертикальная координата левого верхнего угла окна. |
| zoom | double | Коэффициент масштабирования. |

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
### createDestination(Page page, double left, double top, double zoom, boolean considerRotation) {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
```
public static XYZExplicitDestination createDestination(Page page, double left, double top, double zoom, boolean considerRotation)
```


Создайте место назначения в указанном месте страницы с учетом поворота страницы, если это необходимо.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница назначения. |
| left | double | Левая позиция на странице. |
| top | double | Верхняя позиция на странице. |
| zoom | double | Коэффициент масштабирования (0 по умолчанию). |
| considerRotation | boolean | Если истина, позиция будет пересчитана в соответствии с поворотом страницы. |

**Возвращает:**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - Целевой объект.
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
### createDestinationToUpperLeftCorner(Page page) {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
```
public static XYZExplicitDestination createDestinationToUpperLeftCorner(Page page)
```


Создать назначение на указанную страницу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница назначения. |

**Возвращает:**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - Целевой объект.
### createDestinationToUpperLeftCorner(Page page, double zoom) {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
```
public static XYZExplicitDestination createDestinationToUpperLeftCorner(Page page, double zoom)
```


Создать пункт назначения в верхнем левом углу указанной страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница назначения. |
| zoom | double | Коэффициент масштабирования. |

**Возвращает:**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - Целевой объект.
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
### getLeft() {#getLeft--}
```
public double getLeft()
```


Получает левую горизонтальную координату левого верхнего угла окна.

**Возвращает:**
двойной - двойной
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


Получает верхнюю вертикальную координату левого верхнего угла окна.

**Возвращает:**
двойной - двойной
### getZoom() {#getZoom--}
```
public double getZoom()
```


Получает коэффициент масштабирования.

**Возвращает:**
двойной - двойной
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


Преобразует состояние объекта в строковое значение. Пример: «1 XYZ 100 200 3».

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
