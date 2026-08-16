---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Справочник API Aspose.PDF для Java"
description: "Указывает таблицу кодировок. Каждая таблица кодировок имеет уникальное сочетание параметров (PlatformID, PlatformSpecificID). Перечисление {@code CMapEncodingTableType} и свойство."
type: docs
weight: 3700
url: /ru/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Указывает таблицу кодировок. Каждая таблица кодировок имеет уникальное сочетание параметров (PlatformID, PlatformSpecificID). Перечисление {@code CMapEncodingTableType} и свойство {@code CMapEncodingTable} были реализованы для упрощения установки необходимой таблицы кодировок.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [QueueItem](#QueueItem--) | Конструктор, по умолчанию указывает mac‑таблицу (1,0). |
| [QueueItem](#QueueItem-int-int-) | Конструктор |
| [QueueItem](#QueueItem-short-) | Конструктор |

## Методы

| Метод | Описание |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Указывает таблицу кодировок через перечисление {@code CMapEncodingTableType}. |
| [getPlatformId](#getPlatformId--) | Идентификатор платформы для таблицы кодировок. |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Идентификатор специфической кодировки платформы для таблицы кодировок. |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Указывает таблицу кодировок через перечисление {@code CMapEncodingTableType}. |
| [setPlatformId](#setPlatformId-int-) | Идентификатор платформы для таблицы кодировок. |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Идентификатор специфической кодировки платформы для таблицы кодировок. |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Конструктор, по умолчанию указывает mac‑таблицу (1,0).

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Конструктор

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| platformID |  | Идентификатор платформы для таблицы кодировок. |
| platformSpecificID |  | Идентификатор специфической кодировки платформы для таблицы кодировок. |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Конструктор

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmapTable |  | таблица кодировок |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Указывает таблицу кодировок через перечисление {@code CMapEncodingTableType}.

**Returns:**
таблица кодировок

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Идентификатор платформы для таблицы кодировок.

**Returns:**
int значение

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Идентификатор специфической кодировки платформы для таблицы кодировок.

**Returns:**
int значение

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Указывает таблицу кодировок через перечисление {@code CMapEncodingTableType}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | таблица кодировок |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Идентификатор платформы для таблицы кодировок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Идентификатор специфической кодировки платформы для таблицы кодировок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |
