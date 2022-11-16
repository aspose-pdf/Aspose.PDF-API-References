---
title: Table
second_title: Aspose.PDF для справки по Java API
description: Представляет таблицу, которую можно добавить на страницу.
type: docs
weight: 352
url: /ru/java/com.aspose.pdf/table/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Table extends BaseParagraph
```

Представляет таблицу, которую можно добавить на страницу.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Table()](#Table--) | Стор по умолчанию |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонируйте таблицу. |
| [drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-) | Добавьте операторы для прямоугольника. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Получает выравнивание таблицы. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона таблицы |
| [getBorder()](#getBorder--) | Получает границу. |
| [getBreakText()](#getBreakText--) | Получает текст разрыва для таблицы |
| [getBroken()](#getBroken--) | Получает или устанавливает вертикальную неработающую таблицу; |
| [getClass()](#getClass--) |  |
| [getColumnAdjustment()](#getColumnAdjustment--) | Получает настройку столбца таблицы. |
| [getColumnWidth(String stringColumnWidth)](#getColumnWidth-java.lang.String-) | Получить ширину столбца |
| [getColumnWidths()](#getColumnWidths--) | Получает ширину столбцов таблицы. |
| [getCornerStyle()](#getCornerStyle--) | Получает стили граничных углов |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Получает границу ячейки по умолчанию; |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Получает заполнение ячейки по умолчанию. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Получает состояние текста ячейки по умолчанию. |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | Получает границу ячейки по умолчанию; |
| [getHeight()](#getHeight--) | Получить высоту. |
| [getHeight(Page parentPage)](#getHeight-com.aspose.pdf.Page-) | Получить высоту. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getLeft()](#getLeft--) | Получает левую координату таблицы. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | Получает или задает максимальное количество столбцов для таблицы |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | Получает количество первых строк, повторяющихся для нескольких страниц |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | Получает стиль для повторяющихся строк |
| [getRows()](#getRows--) | Получает строки таблицы. |
| [getTop()](#getTop--) | Получает координату столешницы. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getWidth()](#getWidth--) | Получите ширину. |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [isBordersIncluded()](#isBordersIncluded--) | Получает границу, включенную в ширину столбцов. |
| [isBroken()](#isBroken--) | Получает, что таблица сломана - будет усечена для следующей страницы. |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Устанавливает выравнивание таблицы. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Устанавливает цвет фона таблицы |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Устанавливает границу. |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | Устанавливает границу, включенную в ширину столбца. |
| [setBreakText(TextFragment value)](#setBreakText-com.aspose.pdf.TextFragment-) | Устанавливает текст разрыва для таблицы |
| [setBroken(boolean value)](#setBroken-boolean-) | Устанавливает, что таблица сломана - будет усечена для следующей страницы. |
| [setBroken(int value)](#setBroken-int-) | Получает или устанавливает вертикальную неработающую таблицу; |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | Устанавливает настройку столбца таблицы. |
| [setColumnTextState(int colNumber, TextState textState)](#setColumnTextState-int-com.aspose.pdf.TextState-) | Установить высоту. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Получает ширину столбцов таблицы. |
| [setCornerStyle(int value)](#setCornerStyle-int-) | Получает или задает стили углов границы |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Получает границу ячейки по умолчанию; |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Устанавливает заполнение ячейки по умолчанию. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Задает состояние текста ячейки по умолчанию. |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | Получает границу ячейки по умолчанию; |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setLeft(float value)](#setLeft-float-) | Устанавливает левую координату стола. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | Получает или задает максимальное количество столбцов для таблицы |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | Получает количество первых строк, повторяющихся для нескольких страниц |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Получает стиль для повторяющихся строк |
| [setTop(float value)](#setTop-float-) | Устанавливает координату столешницы. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Table() {#Table--}
```
public Table()
```


Стор по умолчанию

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонируйте таблицу.

**Возвращает:**
java.lang.Object — клонированный объект
### drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius) {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-}
```
public static void drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)
```


Добавьте операторы для прямоугольника.

Только для внутреннего использования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| info | [GraphInfo](../../com.aspose.pdf/graphinfo) | Стиль границы. |
| topLeft | [Point](../../com.aspose.pdf/point) | Левая верхняя точка. |
| rightBottom | [Point](../../com.aspose.pdf/point) | Правая нижняя точка. |
| operators | java.util.List<com.aspose.pdf.Operator> | Список операторов для добавления в содержимое страницы. |
| radius | double | Радиус границы. |

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
public final int getAlignment()
```


Получает выравнивание таблицы.

**Возвращает:**
int - значение HorizontalAlignment
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Получает цвет фона таблицы

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цвет объекта
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Получает границу.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - объект BorderInfo
### getBreakText() {#getBreakText--}
```
public final TextFragment getBreakText()
```


Получает текст разрыва для таблицы

**Возвращает:**
[TextFragment](../../com.aspose.pdf/textfragment) Объект TextFragment
### getBroken() {#getBroken--}
```
public final int getBroken()
```


Получает или устанавливает вертикальную неработающую таблицу;

**Возвращает:**
int - значение TableBroken
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


Получает настройку столбца таблицы.

**Возвращает:**
int - значение настройки столбца
### getColumnWidth(String stringColumnWidth) {#getColumnWidth-java.lang.String-}
```
public static double getColumnWidth(String stringColumnWidth)
```


Получить ширину столбца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stringColumnWidth | java.lang.String | Строковое представление. |

**Возвращает:**
двойное - двойное значение
### getColumnWidths() {#getColumnWidths--}
```
public final String getColumnWidths()
```


Получает ширину столбцов таблицы.

**Возвращает:**
java.lang.String — строковое значение
### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


Получает стили граничных углов

**Возвращает:**
int — значение бордеркорнерстиле
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


Получает границу ячейки по умолчанию;

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - объект BorderInfo
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


Получает заполнение ячейки по умолчанию.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Объект MarginInfo
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Получает состояние текста ячейки по умолчанию.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Значение TextState
### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


Получает границу ячейки по умолчанию;

**Возвращает:**
java.lang.String — строковый объект
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получить высоту.

**Возвращает:**
double - высота стола
### getHeight(Page parentPage) {#getHeight-com.aspose.pdf.Page-}
```
public double getHeight(Page parentPage)
```


Получить высоту.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentPage | [Page](../../com.aspose.pdf/page) | Родительская страница таблицы |

**Возвращает:**
double - высота стола
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
public final float getLeft()
```


Получает левую координату таблицы.

**Возвращает:**
float - плавающее значение
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


Получает или задает максимальное количество столбцов для таблицы

**Возвращает:**
интервал - целочисленное значение
### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


Получает количество первых строк, повторяющихся для нескольких страниц

**Возвращает:**
интервал - целочисленное значение
### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


Получает стиль для повторяющихся строк

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Объект TextState
### getRows() {#getRows--}
```
public final Rows getRows()
```


Получает строки таблицы.

**Возвращает:**
[Rows](../../com.aspose.pdf/rows) - Объект строк
### getTop() {#getTop--}
```
public final float getTop()
```


Получает координату столешницы.

**Возвращает:**
float - плавающее значение
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


Получите ширину.

**Возвращает:**
double - Ширина таблицы
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
### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


Получает границу, включенную в ширину столбцов.

**Возвращает:**
boolean - логическое значение
### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


Получает, что таблица сломана - будет усечена для следующей страницы.

**Возвращает:**
boolean - логическое значение
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
public final void setAlignment(int value)
```


Устанавливает выравнивание таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Устанавливает цвет фона таблицы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Цвет объекта |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Устанавливает границу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Объект BorderInfo |

### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


Устанавливает границу, включенную в ширину столбца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBreakText(TextFragment value) {#setBreakText-com.aspose.pdf.TextFragment-}
```
public final void setBreakText(TextFragment value)
```


Устанавливает текст разрыва для таблицы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | Объект TextFragment |

### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


Устанавливает, что таблица сломана - будет усечена для следующей страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


Получает или устанавливает вертикальную неработающую таблицу;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение TableBroken |

### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


Устанавливает настройку столбца таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение регулировки столбца |

### setColumnTextState(int colNumber, TextState textState) {#setColumnTextState-int-com.aspose.pdf.TextState-}
```
public void setColumnTextState(int colNumber, TextState textState)
```


Установить высоту.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| colNumber | int | Номер столбца. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Состояние текста для столбца. |

### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public final void setColumnWidths(String value)
```


Получает ширину столбцов таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


Получает или задает стили углов границы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение Бордеркорнерстиле |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


Получает границу ячейки по умолчанию;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Объект BorderInfo |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


Устанавливает заполнение ячейки по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Задает состояние текста ячейки по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Значение TextState |

### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


Получает границу ячейки по умолчанию;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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

### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


Устанавливает левую координату стола.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


Получает или задает максимальное количество столбцов для таблицы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


Получает количество первых строк, повторяющихся для нескольких страниц

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


Получает стиль для повторяющихся строк

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Объект TextState |

### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


Устанавливает координату столешницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

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
