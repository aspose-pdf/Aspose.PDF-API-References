---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс, представляющий события"
type: docs
weight: 740
url: /ru/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Класс, представляющий события

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [add](#add-T-) | Добавить ещё один делегат. |
| [assign](#assign-T-) | Добавить только текущий делегат, очистив остальные. |
| [clear](#clear--) | Очистить список делегатов |
| [isEmpty](#isEmpty--) | Возвращает true, если список обработчиков пуст |
| [remove](#remove-T-) | Удалить делегат из списка |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Добавить ещё один делегат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| делегат |  | Объект обработчиков |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Добавить только текущий делегат, очистив остальные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| делегат |  | Объект обработчиков |

### clear {#clear--}
```
public final void clear()
```

Очистить список делегатов

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Возвращает true, если список обработчиков пуст

**Returns:**
логическое значение

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Удалить делегат из списка

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| делегат |  | Объект обработчиков |
