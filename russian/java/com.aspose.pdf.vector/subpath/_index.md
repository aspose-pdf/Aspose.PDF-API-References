---
title: "SubPath"
linktitle: "SubPath"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет объект векторной графики на странице. По сути, объекты векторной графики представлены двумя группами SubPath. Одна из них представлена набором линий и."
type: docs
weight: 60
url: /ru/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Представляет объект векторной графики на странице. По сути, объекты векторной графики представлены двумя группами SubPath. Одна из них состоит из набора линий и кривых. Другие представлены в виде прямоугольников и иногда могут быть спутаны. Обычно это прямоугольная область, имеющая цвет, но часто этот прямоугольник размещается в начале страницы и определяет всё пространство страницы белым цветом. Таким образом, вы получаете SubPath, но визуально видите только текст на странице.

## Методы

| Метод | Описание |
| --- | --- |
| [getRectangle](#getRectangle--) | Получает ограничивающий прямоугольник GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Получает ограничивающий прямоугольник GraphicElement.

**Returns:**
Экземпляр Rectangle
