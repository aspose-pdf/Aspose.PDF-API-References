---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет размещение XForm. Если XForm отображается на странице более 1 раза, все XformPlacements, связанные с этим XForm, будут иметь общие графические элементы, но."
type: docs
weight: 70
url: /ru/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Представляет размещение XForm. Если XForm отображается на странице более одного раза, все XformPlacements, связанные с этим XForm, будут иметь общие графические элементы, но разные графические состояния.

## Методы

| Метод | Описание |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Добавляет текущий элемент на страницу. Если элементов много, лучше использовать Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Получает графические элементы внутри этого XForm. |
| [getName](#getName--) | Получает имя XForm. |
| [getRectangle](#getRectangle--) | Получает ограничивающий прямоугольник GraphicElement. |
| [getXForm](#getXForm--) | Получает XForm, связанный с этим XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Получает или задает позицию в текущем координатном пространстве. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Добавляет текущий элемент на страницу. Если элементов много, лучше использовать Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Получает графические элементы внутри этого XForm.

**Returns:**
Экземпляр GraphicElementCollection

### getName {#getName--}
```
public final String getName()
```

Получает имя XForm.

**Returns:**
строковое значение

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Получает ограничивающий прямоугольник GraphicElement.

**Returns:**
Экземпляр Rectangle

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Получает XForm, связанный с этим XFormPlacement.

**Returns:**
Экземпляр XForm

### setPosition {#setPosition-com.aspose.pdf.Point-}
Получает или задает позицию в текущем координатном пространстве.
