---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет объект‑поглотитель графических элементов. Выполняет поиск графики и предоставляет доступ к результатам поиска через {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /ru/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Представляет объект‑поглотитель графических элементов. Выполняет поиск графики и предоставляет доступ к результатам поиска через коллекцию {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [dispose](#dispose--) | Освобождает все ресурсы, используемые классом {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | Получает коллекцию найденных вхождений, представленных объектами {@link GraphicElement}. |
| [resumeUpdate](#resumeUpdate--) | Возобновляет обновление forPage#getContents и всех @link XForm#getContents. Было сделано для повышения производительности, см. также. |
| [suppressUpdate](#suppressUpdate--) | Подавляет обновление для Page#getContents и всех @link XForm#getContents. Было сделано для повышения производительности, см. также. |
| [visit](#visit-com.aspose.pdf.Page-) | Выполняет поиск на указанной странице. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Освобождает все ресурсы, используемые классом {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Получает коллекцию найденных вхождений, представленных объектами {@link GraphicElement}.

**Returns:**
Экземпляр GraphicElementCollection

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Возобновляет обновление forPage#getContents и всех @link XForm#getContents. Было сделано для повышения производительности, см. также.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Подавляет обновление для Page#getContents и всех @link XForm#getContents. Было сделано для повышения производительности, см. также.

### visit {#visit-com.aspose.pdf.Page-}
Выполняет поиск на указанной странице.
