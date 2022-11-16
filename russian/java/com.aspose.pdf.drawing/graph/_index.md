---
title: Graph
second_title: Aspose.PDF для справки по Java API
description: Представляет график - параграф генератора графики.
type: docs
weight: 16
url: /ru/java/com.aspose.pdf.drawing/graph/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Graph extends BaseParagraph
```

Представляет график - параграф генератора графики.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Graph()](#Graph--) | Только для внутреннего использования |
| [Graph(float width, float height)](#Graph-float-float-) | Инициализирует новый экземпляр класса Graph. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонируйте график. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorder()](#getBorder--) | Получает границу. |
| [getClass()](#getClass--) |  |
| [getGraphInfo()](#getGraphInfo--) | Получает объект GraphInfo, который указывает информацию о графике, такую как цвет, ширина линии и т. д. |
| [getHeight()](#getHeight--) | Получает значение с плавающей запятой, указывающее высоту графика. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getLeft()](#getLeft--) | Получает левую координату таблицы. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getShapes()](#getShapes--) | Получает коллекцию Shapes, в которой указаны все фигуры на графике. |
| [getTitle()](#getTitle--) | Получает строковое значение, указывающее заголовок графика. |
| [getTop()](#getTop--) | Получает координату столешницы. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getWidth()](#getWidth--) | Получает значение с плавающей запятой, указывающее ширину графика. |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [isChangePosition()](#isChangePosition--) | Получает изменение текущей позиции после абзаца процесса. |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Устанавливает границу. |
| [setChangePosition(boolean value)](#setChangePosition-boolean-) | Устанавливает изменение текущей позиции после абзаца процесса. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setGraphInfo(GraphInfo value)](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Получает или задает объект GraphInfo, указывающий сведения о графике, такие как цвет, ширина линии и т. д. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает плавающее значение, указывающее высоту графика. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setLeft(double value)](#setLeft-double-) | Устанавливает левую координату стола. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setShapes(List<Shape> value)](#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--) | Задает коллекцию Shapes, которая указывает все фигуры на графике. |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | Задает строковое значение, указывающее заголовок графика. |
| [setTop(double value)](#setTop-double-) | Устанавливает координату столешницы. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setWidth(double value)](#setWidth-double-) | Устанавливает плавающее значение, указывающее ширину графика. |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graph() {#Graph--}
```
public Graph()
```


Только для внутреннего использования

### Graph(float width, float height) {#Graph-float-float-}
```
public Graph(float width, float height)
```


Инициализирует новый экземпляр класса Graph.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Ширина графика. |
| height | float | Высота графика. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонируйте график.

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
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Получает границу.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) Элемент BorderInfo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getGraphInfo() {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```


Получает объект GraphInfo, который указывает информацию о графике, такую как цвет, ширина линии и т. д.

**Возвращает:**
[GraphInfo](../../com.aspose.pdf/graphinfo) - объект GraphInfo
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает значение с плавающей запятой, указывающее высоту графика. Единица точечная. В XML единицей измерения по умолчанию являются точки, но также поддерживаются сантиметры и дюймы. Например, GraphHeight="10cm" или GraphHeight="5inch".

**Возвращает:**
double - значение, указывающее высоту графика.
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
### getShapes() {#getShapes--}
```
public List<Shape> getShapes()
```


Получает коллекцию Shapes, в которой указаны все фигуры на графике.

**Возвращает:**
java.util.List<com.aspose.pdf.drawing.Shape> — Список элементов формы
### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


Получает строковое значение, указывающее заголовок графика.

**Возвращает:**
[TextFragment](../../com.aspose.pdf/textfragment) - название графика.
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


Получает значение с плавающей запятой, указывающее ширину графика. Единица точечная. В XML единицей измерения по умолчанию являются точки, но также поддерживаются сантиметры и дюймы. Например, GraphWidth="10cm" или GraphWidth="5inch".

**Возвращает:**
double - значение с плавающей запятой, указывающее ширину графика.
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
### isChangePosition() {#isChangePosition--}
```
public boolean isChangePosition()
```


Получает изменение текущей позиции после абзаца процесса. (по умолчанию true)

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




### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Устанавливает границу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Элемент BorderInfo |

### setChangePosition(boolean value) {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```


Устанавливает изменение текущей позиции после абзаца процесса. (по умолчанию true)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setGraphInfo(GraphInfo value) {#setGraphInfo-com.aspose.pdf.GraphInfo-}
```
public void setGraphInfo(GraphInfo value)
```


Получает или задает объект GraphInfo, указывающий сведения о графике, такие как цвет, ширина линии и т. д.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | Объект GraphInfo |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Устанавливает плавающее значение, указывающее высоту графика. Единица точечная. В XML единицей измерения по умолчанию являются точки, но также поддерживаются сантиметры и дюймы. Например, GraphHeight="10cm" или GraphHeight="5inch".

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | что указывает на высоту графика. |

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

### setShapes(List<Shape> value) {#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--}
```
public void setShapes(List<Shape> value)
```


Задает коллекцию Shapes, которая указывает все фигуры на графике.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.drawing.Shape> | Список элементов формы |

### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


Задает строковое значение, указывающее заголовок графика.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | название графика. |

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


Устанавливает плавающее значение, указывающее ширину графика. Единица точечная. В XML единицей измерения по умолчанию являются точки, но также поддерживаются сантиметры и дюймы. Например, GraphWidth="10cm" или GraphWidth="5inch".

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | плавающее значение, указывающее ширину графика. |

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
