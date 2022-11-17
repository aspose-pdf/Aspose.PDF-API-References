---
title: FloatingBox
second_title: Aspose.PDF для справки по Java API
description: Представляет FloatingBox в документе Pdf.
type: docs
weight: 128
url: /ru/java/com.aspose.pdf/floatingbox/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public class FloatingBox extends BaseParagraph
```

Представляет FloatingBox в документе Pdf. FloatingBox позиционируется на заказ.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FloatingBox(float width, float height)](#FloatingBox-float-float-) | Инициализирует новый экземпляр класса FloatingBox с заданными шириной и высотой. |
| [FloatingBox()](#FloatingBox--) | Инициализирует новый экземпляр класса FloatingBox. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонирует новый объект FloatingBox. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Получает объект, указывающий цвет фона плавающего блока. |
| [getBackgroundImage()](#getBackgroundImage--) | Получает или задает фоновое изображение для страницы (только для генератора). |
| [getBorder()](#getBorder--) | Получает объект, указывающий информацию о границе плавающего блока. |
| [getClass()](#getClass--) |  |
| [getColumnInfo()](#getColumnInfo--) | Получает информацию о столбце |
| [getHeight()](#getHeight--) | Получает значение с плавающей запятой, указывающее высоту плавающего блока. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getLeft()](#getLeft--) | Получает левую координату таблицы. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getPadding()](#getPadding--) | Получает объект, указывающий заполнение плавающего блока. |
| [getParagraphs()](#getParagraphs--) | Получает коллекцию, указывающую все абзацы в ячейке. |
| [getTop()](#getTop--) | Получает координату столешницы. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getWidth()](#getWidth--) | Получает значение с плавающей запятой, указывающее ширину плавающего блока. |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [isNeedRepeating()](#isNeedRepeating--) | Получает логическое значение, указывающее, нужно ли повторять абзац на следующей странице. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Задает объект, указывающий цвет фона плавающего блока. |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Получает или задает фоновое изображение для страницы (только для генератора). |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Устанавливает объект, который указывает информацию о границе плавающего блока. |
| [setColumnInfo(ColumnInfo value)](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Устанавливает информацию о столбце |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setHeight(double value)](#setHeight-double-) | Задает значение с плавающей запятой, указывающее высоту плавающего блока. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setLeft(double value)](#setLeft-double-) | Устанавливает левую координату стола. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setNeedRepeating(boolean value)](#setNeedRepeating-boolean-) | Задает логическое значение, указывающее, нужно ли повторять абзац на следующей странице. |
| [setPadding(MarginInfo value)](#setPadding-com.aspose.pdf.MarginInfo-) | Задает объект, указывающий заполнение плавающего блока. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Задает коллекцию, которая указывает все абзацы в ячейке. |
| [setTop(double value)](#setTop-double-) | Устанавливает координату столешницы. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setWidth(double value)](#setWidth-double-) | Задает значение с плавающей запятой, указывающее ширину плавающего блока. |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FloatingBox(float width, float height) {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```


Инициализирует новый экземпляр класса FloatingBox с заданными шириной и высотой.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Ширина коробки. |
| height | float | Высота коробки. |

### FloatingBox() {#FloatingBox--}
```
public FloatingBox()
```


Инициализирует новый экземпляр класса FloatingBox.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонирует новый объект FloatingBox. Абзацы в плавающем окне не клонируются.

**Возвращает:**
java.lang.Object — новый объект FloatingBox.
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


Получает объект, указывающий цвет фона плавающего блока.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - объект, указывающий цвет фона.
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Получает или задает фоновое изображение для страницы (только для генератора).

**Возвращает:**
[Image](../../com.aspose.pdf/image) - Экземпляр изображения
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Получает объект, указывающий информацию о границе плавающего блока.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - объект, указывающий информацию о границе.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColumnInfo() {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```


Получает информацию о столбце

**Возвращает:**
[ColumnInfo](../../com.aspose.pdf/columninfo) - объект ColumnInfo
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает значение с плавающей запятой, указывающее высоту плавающего блока.

**Возвращает:**
double - значение, указывающее высоту.
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание абзаца

**Возвращает:**
int - значение HorizontalAlignment
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Получает гиперссылку фрагмента (для генератора pdf).

**Возвращает:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - гиперссылка на фрагмент (для генератора pdf).
### getLeft() {#getLeft--}
```
public double getLeft()
```


Получает левую координату таблицы.

**Возвращает:**
double - левая координата стола.
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getPadding() {#getPadding--}
```
public MarginInfo getPadding()
```


Получает объект, указывающий заполнение плавающего блока.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - объект, указывающий заполнение.
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Получает коллекцию, указывающую все абзацы в ячейке.

**Возвращает:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - коллекция, указывающая на все абзацы.
### getTop() {#getTop--}
```
public double getTop()
```


Получает координату столешницы.

**Возвращает:**
double - координата столешницы.
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание абзаца

**Возвращает:**
int - элемент вертикального выравнивания
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает значение с плавающей запятой, указывающее ширину плавающего блока.

**Возвращает:**
двойное - двойное значение
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Получает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Получает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isNeedRepeating() {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```


Получает логическое значение, указывающее, нужно ли повторять абзац на следующей странице. Значение по умолчанию — true. Атрибут действителен, только если сам абзац и объект, на который ссылается его ReferenceParagraphID, включены в RepeatingRows.

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


Задает объект, указывающий цвет фона плавающего блока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | объект, указывающий цвет фона. |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Получает или задает фоновое изображение для страницы (только для генератора).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Экземпляр изображения |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Устанавливает объект, который указывает информацию о границе плавающего блока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | объект, который указывает информацию о границе. |

### setColumnInfo(ColumnInfo value) {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
```
public void setColumnInfo(ColumnInfo value)
```


Устанавливает информацию о столбце

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColumnInfo](../../com.aspose.pdf/columninfo) | значение ColumnInfo |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Задает значение с плавающей запятой, указывающее высоту плавающего блока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | значение, указывающее высоту. |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает горизонтальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Устанавливает гиперссылку (для генератора pdf).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | гиперссылка (для генератора pdf). |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Устанавливает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLeft(double value) {#setLeft-double-}
```
public void setLeft(double value)
```


Устанавливает левую координату стола.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | левая координата стола. |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setNeedRepeating(boolean value) {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```


Задает логическое значение, указывающее, нужно ли повторять абзац на следующей странице. Значение по умолчанию — true. Атрибут действителен, только если сам абзац и объект, на который ссылается его ReferenceParagraphID, включены в RepeatingRows.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPadding(MarginInfo value) {#setPadding-com.aspose.pdf.MarginInfo-}
```
public void setPadding(MarginInfo value)
```


Задает объект, указывающий заполнение плавающего блока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | объект, указывающий заполнение. |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Задает коллекцию, которая указывает все абзацы в ячейке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | коллекция, которая указывает все абзацы. |

### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```


Устанавливает координату столешницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | координата столешницы. |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Задает значение с плавающей запятой, указывающее ширину плавающего блока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

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
