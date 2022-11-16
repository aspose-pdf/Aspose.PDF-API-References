---
title: Cell
second_title: Aspose.PDF для справки по Java API
description: Представляет ячейку строки таблицы.
type: docs
weight: 52
url: /ru/java/com.aspose.pdf/cell/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.ICloneable
```
public final class Cell implements System.ICloneable
```

Представляет ячейку строки таблицы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Cell(Rectangle rect)](#Cell-com.aspose.pdf.Rectangle-) | Инициализирует новый экземпляр класса Cell. |
| [Cell()](#Cell--) | Инициализирует новый экземпляр класса Cell. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонируйте ячейку. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Получает выравнивание. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона. |
| [getBackgroundImage()](#getBackgroundImage--) | Получает или задает фоновое изображение |
| [getBackgroundImageFile()](#getBackgroundImageFile--) | Получает файл фонового изображения. |
| [getBorder()](#getBorder--) | Получает границу. |
| [getClass()](#getClass--) |  |
| [getColSpan()](#getColSpan--) | Получает или задает диапазон столбцов. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Получает состояние текста ячейки по умолчанию. |
| [getMargin()](#getMargin--) | Получает прокладку. |
| [getParagraphs()](#getParagraphs--) | Получает отформатированный текст ячейки. |
| [getRowSpan()](#getRowSpan--) | Получает диапазон строк. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание. |
| [getWidth()](#getWidth--) | Получает ширину столбца. |
| [hashCode()](#hashCode--) |  |
| [isNoBorder()](#isNoBorder--) | Получает ячейку с границей. |
| [isOverrideByFragment()](#isOverrideByFragment--) | Устанавливает, что свойство TextState ячейки переопределяется свойством TextFragment TextState. |
| [isWordWrapped()](#isWordWrapped--) | Получает обертку текстового слова ячейки. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Устанавливает выравнивание. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Получает или задает цвет фона. |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Получает или задает фоновое изображение |
| [setBackgroundImageFile(String value)](#setBackgroundImageFile-java.lang.String-) | Устанавливает файл фонового изображения. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Устанавливает границу. |
| [setColSpan(int value)](#setColSpan-int-) | Задает диапазон столбцов. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Задает состояние текста ячейки по умолчанию. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает отступ. |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | Устанавливает границу ячейки. |
| [setOverrideByFragment(boolean value)](#setOverrideByFragment-boolean-) | Устанавливает, что свойство TextState ячейки переопределяется свойством TextFragment TextState. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Задает форматированный текст ячейки. |
| [setRowSpan(int value)](#setRowSpan-int-) | Задает диапазон строк. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание. |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину столбца. |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Устанавливает перенос текстового слова ячейки. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cell(Rectangle rect) {#Cell-com.aspose.pdf.Rectangle-}
```
public Cell(Rectangle rect)
```


Инициализирует новый экземпляр класса Cell.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник ячейки в координатах страницы. |

### Cell() {#Cell--}
```
public Cell()
```


Инициализирует новый экземпляр класса Cell.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонируйте ячейку.

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Получает выравнивание.

**Возвращает:**
int - элемент HorizontalAlignment
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет фона.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цвет объекта
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Получает или задает фоновое изображение

**Возвращает:**
[Image](../../com.aspose.pdf/image) - Экземпляр изображения
### getBackgroundImageFile() {#getBackgroundImageFile--}
```
public String getBackgroundImageFile()
```


Получает файл фонового изображения.

**Возвращает:**
java.lang.String — строковое значение
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Получает границу.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - объект BorderInfo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColSpan() {#getColSpan--}
```
public int getColSpan()
```


Получает или задает диапазон столбцов.

**Возвращает:**
интервал - целочисленное значение
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


Получает состояние текста ячейки по умолчанию.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Объект TextState
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает прокладку.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Объект MarginInfo
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Получает отформатированный текст ячейки.

**Возвращает:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - Объект абзацев
### getRowSpan() {#getRowSpan--}
```
public int getRowSpan()
```


Получает диапазон строк.

**Возвращает:**
интервал - целочисленное значение
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание.

**Возвращает:**
int - элемент вертикального выравнивания
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает ширину столбца.

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isNoBorder() {#isNoBorder--}
```
public boolean isNoBorder()
```


Получает ячейку с границей.

**Возвращает:**
boolean - логическое значение
### isOverrideByFragment() {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```


Устанавливает, что свойство TextState ячейки переопределяется свойством TextFragment TextState.

**Возвращает:**
boolean - логическое значение
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Получает обертку текстового слова ячейки.

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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Устанавливает выравнивание.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент HorizontalAlignment |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Получает или задает цвет фона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Цвет объекта |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Получает или задает фоновое изображение

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Экземпляр изображения |

### setBackgroundImageFile(String value) {#setBackgroundImageFile-java.lang.String-}
```
public void setBackgroundImageFile(String value)
```


Устанавливает файл фонового изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Цвет объекта |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Устанавливает границу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Объект BorderInfo |

### setColSpan(int value) {#setColSpan-int-}
```
public void setColSpan(int value)
```


Задает диапазон столбцов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


Задает состояние текста ячейки по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Объект TextState |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает отступ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```


Устанавливает границу ячейки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOverrideByFragment(boolean value) {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```


Устанавливает, что свойство TextState ячейки переопределяется свойством TextFragment TextState.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Задает форматированный текст ячейки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | Объект абзацев |

### setRowSpan(int value) {#setRowSpan-int-}
```
public void setRowSpan(int value)
```


Задает диапазон строк.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает ширину столбца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Устанавливает перенос текстового слова ячейки.

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
