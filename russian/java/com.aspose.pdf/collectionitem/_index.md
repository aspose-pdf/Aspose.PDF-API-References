---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс элемента коллекции. Элемент коллекции содержит данные, описанные схемой коллекции."
type: docs
weight: 640
url: /ru/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Представляет класс элемента коллекции. Элемент коллекции содержит данные, описанные схемой коллекции.

## Методы

| Метод | Описание |
| --- | --- |
| [getAllNames](#getAllNames--) | Получает коллекцию всех имён значений элементов коллекции. |
| [hasName](#hasName-java.lang.String-) | Проверяет, существует ли указанное имя в элементе коллекции. |
| [isEmpty](#isEmpty--) | Получает значение, указывающее, пустой ли элемент коллекции. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Пытается получить значение типа DateTime из элемента коллекции по указанному имени. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Пытается получить значение типа double для указанного имени из элемента коллекции. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Пытается получить целочисленное значение для указанного имени из элемента коллекции. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Пытается получить текстовое значение с указанным именем из элемента коллекции. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Получает коллекцию всех имён значений элементов коллекции.

**Returns:**
список String

### hasName {#hasName-java.lang.String-}
Проверяет, существует ли указанное имя в элементе коллекции.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Получает значение, указывающее, пустой ли элемент коллекции.

**Returns:**
true, если элемент коллекции пуст; иначе — false. Это свойство возвращает true, если элемент коллекции не содержит никаких значений, включая строковые, double, целочисленные и датовые значения. Если любой из этих типов значений присутствует в элементе коллекции, свойство возвращает false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Пытается получить значение типа DateTime из элемента коллекции по указанному имени.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Пытается получить значение типа double для указанного имени из элемента коллекции.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Пытается получить целочисленное значение для указанного имени из элемента коллекции.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Пытается получить текстовое значение с указанным именем из элемента коллекции.
