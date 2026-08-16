---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет коллекцию {@link GraphicElement}."
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Представляет коллекцию {@link GraphicElement}.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Инициализирует новую коллекцию. |

## Методы

| Метод | Описание |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Добавляет новый {@link GraphicElement} в коллекцию. Все элементы в коллекции должны иметь одинаковый {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | Очищает коллекцию. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Определяет, находится ли элемент в коллекции. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Копирует всю коллекцию в совместимый одномерный массив Array, начиная с указанного индекса целевого массива. |
| [get_Item](#get_Item-int-) | Получает элемент {@link GraphicElement} по указанному индексу. |
| [isReadOnly](#isReadOnly--) | Получает значение, указывающее, является ли коллекция только для чтения. Всегда возвращает false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Возвращает перечислитель для всей коллекции. |
| [iterator](#iterator--) | Возвращает перечислитель для всей коллекции. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Удаляет элемент {@link GraphicElement}. |
| [size](#size--) | Получает количество объектов {@link GraphicElement}, фактически содержащихся в коллекции. |
| [toList](#toList--) | Возвращает внутреннюю коллекцию для неограниченного перечисления. |
| [toString](#toString--) | Получает строковое представление этой коллекции. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Инициализирует новую коллекцию.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Добавляет новый {@link GraphicElement} в коллекцию. Все элементы в коллекции должны иметь одинаковый {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Очищает коллекцию.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Определяет, находится ли элемент в коллекции.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Копирует всю коллекцию в совместимый одномерный массив Array, начиная с указанного индекса целевого массива.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Получает элемент {@link GraphicElement} по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс |  | Индекс в коллекции. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли коллекция только для чтения. Всегда возвращает false.

**Returns:**
логическое значение

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Возвращает перечислитель для всей коллекции.

**Returns:**
Объект перечислителя.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Возвращает перечислитель для всей коллекции.

**Returns:**
Объект перечислителя.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Удаляет элемент {@link GraphicElement}.

### size {#size--}
```
public final int size()
```

Получает количество объектов {@link GraphicElement}, фактически содержащихся в коллекции.

**Returns:**
int значение

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Возвращает внутреннюю коллекцию для неограниченного перечисления.

**Returns:**
Внутренний список

### toString {#toString--}
```
public String toString()
```

Получает строковое представление этой коллекции.

**Returns:**
Строка.
