---
title: Row
second_title: Aspose.PDF для справки по Java API
description: Представляет строку таблицы.
type: docs
weight: 316
url: /ru/java/com.aspose.pdf/row/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.ICloneable
```
public final class Row implements System.ICloneable
```

Представляет строку таблицы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Row()](#Row--) | Инициализирует новый экземпляр класса Row. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонируйте строку. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона. |
| [getBorder()](#getBorder--) | Получает границу. |
| [getCells()](#getCells--) | Получает getCells() строки. |
| [getClass()](#getClass--) |  |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Получает границу ячейки по умолчанию; |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Получает поле по умолчанию для строки getCells() |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Получает или устанавливает состояние текста по умолчанию для строки getCells() |
| [getFixedRowHeight()](#getFixedRowHeight--) | Получает фиксированную высоту строки — строка может иметь фиксированную высоту; |
| [getMinRowHeight()](#getMinRowHeight--) | Получает высоту строки; |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает или задает вертикальное выравнивание. |
| [hashCode()](#hashCode--) |  |
| [isInNewPage()](#isInNewPage--) | Получает фиксированную строку на новой странице — страница с этим свойством должна быть напечатана на следующей странице. По умолчанию false; |
| [isRowBroken()](#isRowBroken--) | Получает, что строка может быть разбита между двумя страницами |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Устанавливает цвет фона. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Устанавливает границу. |
| [setCells(Cells value)](#setCells-com.aspose.pdf.Cells-) | Устанавливает getCells() строки. |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Устанавливает границу ячейки по умолчанию; |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Устанавливает поле по умолчанию для строки getCells() |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Устанавливает состояние текста по умолчанию для строки getCells() |
| [setFixedRowHeight(double value)](#setFixedRowHeight-double-) | Устанавливает фиксированную высоту строки — строка может иметь фиксированную высоту; |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Наборы - это строка, которая может быть разбита между двумя страницами |
| [setMinRowHeight(double value)](#setMinRowHeight-double-) | Устанавливает высоту строки; |
| [setRowBroken(boolean value)](#setRowBroken-boolean-) | Наборы - это строка, которая может быть разбита между двумя страницами |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Получает или задает вертикальное выравнивание. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Row() {#Row--}
```
public Row()
```


Инициализирует новый экземпляр класса Row.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонируйте строку.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет фона.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Значение цвета
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Получает границу.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - Значение пограничной информации
### getCells() {#getCells--}
```
public Cells getCells()
```


Получает getCells() строки.

**Возвращает:**
[Cells](../../com.aspose.pdf/cells) - значение getCells()
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```


Получает границу ячейки по умолчанию;

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - Значение пограничной информации
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```


Получает поле по умолчанию для строки getCells()

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


Получает или устанавливает состояние текста по умолчанию для строки getCells()

Получает состояние текста по умолчанию для строки getCells()

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Значение TextState
### getFixedRowHeight() {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```


Получает фиксированную высоту строки — строка может иметь фиксированную высоту;

**Возвращает:**
двойное - двойное значение
### getMinRowHeight() {#getMinRowHeight--}
```
public double getMinRowHeight()
```


Получает высоту строки;

**Возвращает:**
двойное - двойное значение
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает или задает вертикальное выравнивание.

**Возвращает:**
int - элемент вертикального выравнивания
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Получает фиксированную строку на новой странице — страница с этим свойством должна быть напечатана на следующей странице. По умолчанию false;

**Возвращает:**
boolean - логическое значение
### isRowBroken() {#isRowBroken--}
```
public boolean isRowBroken()
```


Получает, что строка может быть разбита между двумя страницами

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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает цвет фона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Значение цвета |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Устанавливает границу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Значение BorderInfo |

### setCells(Cells value) {#setCells-com.aspose.pdf.Cells-}
```
public void setCells(Cells value)
```


Устанавливает getCells() строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Cells](../../com.aspose.pdf/cells) | значение getCells() |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public void setDefaultCellBorder(BorderInfo value)
```


Устанавливает границу ячейки по умолчанию;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Значение BorderInfo |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public void setDefaultCellPadding(MarginInfo value)
```


Устанавливает поле по умолчанию для строки getCells()

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Значение MarginInfo |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


Устанавливает состояние текста по умолчанию для строки getCells()

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Значение TextState |

### setFixedRowHeight(double value) {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```


Устанавливает фиксированную высоту строки — строка может иметь фиксированную высоту;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Наборы - это строка, которая может быть разбита между двумя страницами

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMinRowHeight(double value) {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```


Устанавливает высоту строки;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setRowBroken(boolean value) {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```


Наборы - это строка, которая может быть разбита между двумя страницами

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Получает или задает вертикальное выравнивание.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

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
