---
title: PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF для справки по Java API
description: Определяет подтаблицу кодирования.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Наследование:**
java.lang.Object
```
public static class PdfASymbolicFontEncodingStrategy.QueueItem
```

Определяет подтаблицу кодирования. Каждая подтаблица кодирования имеет уникальную комбинацию параметров (PlatformID, PlatformSpecificID). Перечисление CMapEncodingTableType и свойство CMapEncodingTable были реализованы для упрощения набора необходимой подтаблицы кодирования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [QueueItem()](#QueueItem--) | Конструктор, по умолчанию указывает подтаблицу mac(1,0) |
| [QueueItem(int platformID, int platformSpecificID)](#QueueItem-int-int-) | Конструктор |
| [QueueItem(short cmapTable)](#QueueItem-short-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCMapEncodingTable()](#getCMapEncodingTable--) | Указывает подтаблицу кодирования через перечисление CMapEncodingTableType. |
| [getClass()](#getClass--) |  |
| [getPlatformId()](#getPlatformId--) | Идентификатор платформы для подтаблицы кодирования |
| [getPlatformSpecificId()](#getPlatformSpecificId--) | Идентификатор кодировки для конкретной платформы для подтаблицы кодирования |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCMapEncodingTable(short value)](#setCMapEncodingTable-short-) | Указывает подтаблицу кодирования через перечисление CMapEncodingTableType. |
| [setPlatformId(int value)](#setPlatformId-int-) | Идентификатор платформы для подтаблицы кодирования |
| [setPlatformSpecificId(int value)](#setPlatformSpecificId-int-) | Идентификатор кодировки для конкретной платформы для подтаблицы кодирования |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QueueItem() {#QueueItem--}
```
public QueueItem()
```


Конструктор, по умолчанию указывает подтаблицу mac(1,0)

### QueueItem(int platformID, int platformSpecificID) {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| platformID | int | Идентификатор платформы для подтаблицы кодирования |
| platformSpecificID | int | Идентификатор кодировки для конкретной платформы для подтаблицы кодирования |

### QueueItem(short cmapTable) {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmapTable | short | подтаблица кодирования |

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
### getCMapEncodingTable() {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```


Указывает подтаблицу кодирования через перечисление CMapEncodingTableType.

**Возвращает:**
короткая - подтаблица кодирования
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getPlatformId() {#getPlatformId--}
```
public int getPlatformId()
```


Идентификатор платформы для подтаблицы кодирования

**Возвращает:**
интервал - целочисленное значение
### getPlatformSpecificId() {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```


Идентификатор кодировки для конкретной платформы для подтаблицы кодирования

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCMapEncodingTable(short value) {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```


Указывает подтаблицу кодирования через перечисление CMapEncodingTableType.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | подтаблица кодирования |

### setPlatformId(int value) {#setPlatformId-int-}
```
public void setPlatformId(int value)
```


Идентификатор платформы для подтаблицы кодирования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPlatformSpecificId(int value) {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```


Идентификатор кодировки для конкретной платформы для подтаблицы кодирования

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
