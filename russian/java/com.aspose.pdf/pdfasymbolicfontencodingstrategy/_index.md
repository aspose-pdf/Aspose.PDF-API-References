---
title: PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF для справки по Java API
description: Этот класс описывает правила, которые можно использовать для настройки процесса копирования данных кодировки для случаев, когда символьный шрифт TrueType имеет более одной кодировки.
type: docs
weight: 274
url: /ru/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Наследование:**
java.lang.Object
```
public class PdfASymbolicFontEncodingStrategy
```

Этот класс описывает правила, которые можно использовать для настройки процесса копирования данных кодировки для случаев, когда символьный шрифт TrueType имеет более одной кодировки. Некоторые PDF-документы после преобразования в формат PDF/A могут иметь ошибку «Более одной кодировки в cmap символического шрифта TrueType». В чем причина этой ошибки? Все символьные шрифты TrueType имеют в своих внутренних данных специальную таблицу "cmap". Эта таблица сопоставляет коды символов с индексами глифов. И эта таблица может содержать различные подтаблицы кодирования, описывающие используемые кодировки. Дополнительные сведения о таблицах cmap см. на странице https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Обычно таблица cmap содержит несколько подтаблиц кодирования, но стандарт PDF/A требует, чтобы для этого шрифта в документе PDF/A была оставлена только одна подтаблица кодирования (3,0). И ключевой вопрос здесь - какие данные нужно взять из других подтаблиц, чтобы скопировать в целевую таблицу кодирования (3,0)? Большинство шрифтов имеют «правильно сформированные» таблицы cmap, в которых каждая подтаблица кодирования полностью согласуется с другой подтаблицей. Но некоторые шрифты имеют таблицы cmap с коллизиями - например, одна подтаблица имеет индекс глифа 100 для юникода 100, а другая подтаблица имеет индекс глифа 200 для того же юникода 100. Для решения этой проблемы требуется специальная стратегия. По умолчанию используется следующая стратегия: ищется подтаблица mac(1,0). Если эта таблица найдена, только эти данные используются для заполнения таблицы назначения (3,0). Если подтаблица mac не найдена, то все подтаблицы, кроме (3,0), повторяются и используются для копирования данных в подтаблицу назначения (3,0). Также сопоставление для каждого юникода (юникода, индекса глифа) копируется в целевую таблицу, только если в целевой таблице нет этого юникода в текущий момент. Так, например, если первая подтаблица имеет индекс глифа 100 для юникода 100, а следующая подтаблица имеет индекс глифа 200 для того же юникода 100, будут скопированы только данные из первой подтаблицы (юникод = 100, индекс глифа = 100). Таким образом, каждая предыдущая подтаблица имеет приоритет над следующей. Свойства этого класса PdfASymbolicFontEncodingStrategy помогают настроить поведение по умолчанию. Если установлено свойство PreferredCmapEncodingTable типа QueueItem.CMapEncodingTableType, соответствующая подтаблица будет использоваться в приоритете над подтаблицей mac(1,0). Значение 'MacTable' из перечисления QueueItem.CMapEncodingTableType в данном случае не имеет смысла, поскольку оно указывает на ту же подтаблицу mac (1,0), которая будет использоваться по умолчанию. Свойство CmapEncodingTablesPriorityQueue отбрасывает все приоритеты для любой подтаблицы. Если это свойство установлено, то в указанном порядке будут использоваться только подтаблицы из объявленной очереди. Если указанные подтаблицы не найдены, будет использоваться итерация по умолчанию для всех подтаблиц и стратегия копирования, описанная выше. Объект QueueItem указывает используемую подтаблицу кодирования. Эту подтаблицу можно задать с помощью комбинации элементов (PlatformID, PlatformSpecificID) или с помощью перечисления QueueItem.CMapEncodingTableType.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy()](#PdfASymbolicFontEncodingStrategy--) | Конструктор. |
| [PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue)](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--) | Конструктор |
| [PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)](#PdfASymbolicFontEncodingStrategy-short-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCmapEncodingTablesPriorityQueue()](#getCmapEncodingTablesPriorityQueue--) | Указывает очередь подтаблиц кодирования для обработки. |
| [getPreferredCmapEncodingTable()](#getPreferredCmapEncodingTable--) | Указывает подтаблицу, которая будет использоваться в приоритете над подтаблицей mac(1,0). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value)](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--) | Указывает очередь подтаблиц кодирования для обработки. |
| [setPreferredCmapEncodingTable(short value)](#setPreferredCmapEncodingTable-short-) | Указывает подтаблицу, которая будет использоваться в приоритете над подтаблицей mac(1,0). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfASymbolicFontEncodingStrategy() {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```


Конструктор. Устанавливает подтаблицу по умолчанию (mac 1,0)

### PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue) {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--}
```
public PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| priorityQueue | com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> | очередь подтаблиц кодирования для итерации |

### PdfASymbolicFontEncodingStrategy(short preferredEncodingTable) {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| preferredEncodingTable | short | подтаблица кодирования, которая будет использоваться в приоритете над подтаблицей mac(1,0) |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCmapEncodingTablesPriorityQueue() {#getCmapEncodingTablesPriorityQueue--}
```
public System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> getCmapEncodingTablesPriorityQueue()
```


Указывает очередь подтаблиц кодирования для обработки.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> — Очередь из QueueItem
### getPreferredCmapEncodingTable() {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```


Указывает подтаблицу, которая будет использоваться в приоритете над подтаблицей mac(1,0). Значение 'MacTable' из перечисления QueueItem.CMapEncodingTableType в данном случае не имеет смысла.

**Возвращает:**
короткий — элемент CMapEncodingTableType
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




### setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value) {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--}
```
public void setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value)
```


Указывает очередь подтаблиц кодирования для обработки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> | Очередь QueueItem |

### setPreferredCmapEncodingTable(short value) {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```


Указывает подтаблицу, которая будет использоваться в приоритете над подтаблицей mac(1,0). Значение 'MacTable' из перечисления QueueItem.CMapEncodingTableType в данном случае не имеет смысла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | Подтаблица кодирования preferenceEncodingTable, которая будет использоваться в приоритете над подтаблицей mac(1,0) |

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
