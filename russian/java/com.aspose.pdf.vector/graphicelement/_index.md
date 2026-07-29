---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет базовый класс графического объекта на странице."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Представляет базовый класс графического объекта на странице.

## Методы

| Метод | Описание |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Добавляет текущий элемент на страницу. Если элементов много, лучше использовать Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Освобождает все ресурсы, используемые классом {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | Получает матрицу графического элемента. Матрица устанавливается при создании элемента. Она изменяется при вызове SetPosition(). |
| [getOperators](#getOperators--) | Получает коллекцию операторов, представляющих элемент. |
| [getParent](#getParent--) | Получает текущий {@link XFormPlacement}, в котором находится элемент. |
| [getPosition](#getPosition--) | Получает или задает позицию в текущем пространстве координат. Если Parent #getParent/#setParent(XFormPlacement) не равен null, то элемент имеет пространство координат xForm. |
| [getRectangle](#getRectangle--) | Получает ограничивающий прямоугольник {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Получает страницу, из которой извлекается графический элемент. |
| [remove](#remove--) | Удаляет текущий элемент со страницы. Если нужно удалить много элементов, лучше использовать Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Преобразует элемент в одно изображение SVG. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Преобразует элемент в одно изображение SVG. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Получает или задает позицию в текущем пространстве координат. Если Parent #getParent/#setParent(XFormPlacement) не равен null, то элемент имеет пространство координат xForm. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Добавляет текущий элемент на страницу. Если элементов много, лучше использовать Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Освобождает все ресурсы, используемые классом {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Получает матрицу графического элемента. Матрица устанавливается при создании элемента. Она изменяется при вызове SetPosition().

**Returns:**
Экземпляр Matrix

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Получает коллекцию операторов, представляющих элемент.

**Returns:**
Список экземпляров Operator

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Получает текущий {@link XFormPlacement}, в котором находится элемент.

**Returns:**
Экземпляр XFormPlacement

### getPosition {#getPosition--}
```
public Point getPosition()
```

Получает или задает позицию в текущем пространстве координат. Если Parent #getParent/#setParent(XFormPlacement) не равен null, то элемент имеет пространство координат xForm.

**Returns:**
Экземпляр Point

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Получает ограничивающий прямоугольник {@link GraphicElement}.

**Returns:**
Экземпляр Rectangle

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Получает страницу, из которой извлекается графический элемент.

**Returns:**
Экземпляр Page

### remove {#remove--}
```
public final void remove()
```

Удаляет текущий элемент со страницы. Если нужно удалить много элементов, лучше использовать Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Преобразует элемент в одно изображение SVG.

**Returns:**
Строка SVG.

### saveToSvg {#saveToSvg-java.lang.String-}
Преобразует элемент в одно изображение SVG.

**Returns:**
Строка SVG.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Получает или задает позицию в текущем пространстве координат. Если Parent #getParent/#setParent(XFormPlacement) не равен null, то элемент имеет пространство координат xForm.
