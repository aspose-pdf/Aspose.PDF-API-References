---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет контейнерный класс для графических элементов."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Представляет контейнерный класс для графических элементов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Создает экземпляр класса контейнера для графических элементов. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Создает экземпляр класса контейнера для графических элементов. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Создает экземпляр класса контейнера для графических элементов. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Создает экземпляр класса контейнера для графических элементов. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Создает экземпляр класса контейнера для графических элементов. |

## Методы

| Метод | Описание |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Вычисляет расстояние между двумя контейнерами. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Сравнивает текущий объект SubPathContainer с другим объектом SubPathContainer и возвращает целое число, указывающее, меньше ли текущий объект, равен ли он или больше другого объекта. Объекты сравниваются по их числовому идентификатору. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Вычисляет расстояние между этим контейнером и другим контейнером. |
| [getGraphElement](#getGraphElement--) | Получает содержащийся графический элемент. |
| [getId](#getId--) | Получает идентификатор SubPathContainer. Идентификатор необходим для упрощения отладки и сортировки элементов во время рендеринга. |
| [getRect](#getRect--) | Представляет прямоугольник содержащегося элемента. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Создает экземпляр класса контейнера для графических элементов.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Создает экземпляр класса контейнера для графических элементов.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Создает экземпляр класса контейнера для графических элементов.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Создает экземпляр класса контейнера для графических элементов.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Создает экземпляр класса контейнера для графических элементов.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Вычисляет расстояние между двумя контейнерами.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Сравнивает текущий объект SubPathContainer с другим объектом SubPathContainer и возвращает целое число, указывающее, меньше ли текущий объект, равен ли он или больше другого объекта. Объекты сравниваются по их числовому идентификатору.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Вычисляет расстояние между этим контейнером и другим контейнером.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Получает содержащийся графический элемент.

**Returns:**
Экземпляр GraphicElement

### getId {#getId--}
```
public final int getId()
```

Получает идентификатор SubPathContainer. Идентификатор необходим для упрощения отладки и сортировки элементов во время рендеринга.

**Returns:**
int значение

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Представляет прямоугольник содержащегося элемента.

**Returns:**
Экземпляр Rectangle

### toString {#toString--}
```
public String toString()
```

{@code }
