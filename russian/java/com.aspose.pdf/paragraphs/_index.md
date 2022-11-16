---
title: Paragraphs
second_title: Aspose.PDF для справки по Java API
description: Этот класс представляет коллекцию абзацев.
type: docs
weight: 270
url: /ru/java/com.aspose.pdf/paragraphs/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable, com.aspose.ms.System.ICloneable
```
public class Paragraphs implements Iterable<BaseParagraph>, System.ICloneable
```

Этот класс представляет коллекцию абзацев.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Paragraphs()](#Paragraphs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [add(BaseParagraph paragraph)](#add-com.aspose.pdf.BaseParagraph-) | Добавить абзац в коллекцию. |
| [clear()](#clear--) | Очистить абзацы. |
| [deepClone()](#deepClone--) | Клонирует новый объект Clone. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получите количество абзацев. |
| [getRange(int index, int count)](#getRange-int-int-) | Удалить диапазон абзацев. |
| [get_Item(int index)](#get-Item-int-) | Получает абзац из коллекции. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, BaseParagraph paragraph)](#insert-int-com.aspose.pdf.BaseParagraph-) | Вставить абзац в коллекцию. |
| [insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection)](#insertRange-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.BaseParagraph--) | Вставляет элементы коллекции в список по указанному индексу. |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(BaseParagraph paragraph)](#remove-com.aspose.pdf.BaseParagraph-) | Удалить абзац из коллекции. |
| [removeRange(int index, int count)](#removeRange-int-int-) | Удалить диапазон абзацев. |
| [set_Item(int index, BaseParagraph value)](#set-Item-int-com.aspose.pdf.BaseParagraph-) | Устанавливает абзац в коллекцию. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Paragraphs() {#Paragraphs--}
```
public Paragraphs()
```


### add(BaseParagraph paragraph) {#add-com.aspose.pdf.BaseParagraph-}
```
public void add(BaseParagraph paragraph)
```


Добавить абзац в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | Абзац. |

### clear() {#clear--}
```
public void clear()
```


Очистить абзацы.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонирует новый объект Clone.

**Возвращает:**
java.lang.Object — новый объект Clone.
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
### getCount() {#getCount--}
```
public int getCount()
```


Получите количество абзацев.

**Возвращает:**
интервал - целочисленное значение
### getRange(int index, int count) {#getRange-int-int-}
```
public Paragraphs getRange(int index, int count)
```


Удалить диапазон абзацев.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель первого абзаца. |
| count | int | Абзацы считаются. |

**Возвращает:**
[Paragraphs](../../com.aspose.pdf/paragraphs) Коллекция абзацев
### get_Item(int index) {#get-Item-int-}
```
public BaseParagraph get_Item(int index)
```


Получает абзац из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель абзаца. |

**Возвращает:**
[BaseParagraph](../../com.aspose.pdf/baseparagraph) - Объект Базового Параграфа
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### insert(int index, BaseParagraph paragraph) {#insert-int-com.aspose.pdf.BaseParagraph-}
```
public void insert(int index, BaseParagraph paragraph)
```


Вставить абзац в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс абзаца. |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | Абзац. |

### insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection) {#insertRange-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.BaseParagraph--}
```
public void insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection)
```


Вставляет элементы коллекции в список по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целочисленное значение (индекс) |
| collection | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.BaseParagraph> | список объектов BaseParagraph (коллекция) |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```




**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(BaseParagraph paragraph) {#remove-com.aspose.pdf.BaseParagraph-}
```
public void remove(BaseParagraph paragraph)
```


Удалить абзац из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | Объект BaseParagraph |

### removeRange(int index, int count) {#removeRange-int-int-}
```
public void removeRange(int index, int count)
```


Удалить диапазон абзацев.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель первого абзаца. |
| count | int | Абзацы считаются. |

### set_Item(int index, BaseParagraph value) {#set-Item-int-com.aspose.pdf.BaseParagraph-}
```
public void set_Item(int index, BaseParagraph value)
```


Устанавливает абзац в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель абзаца. |
| value | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | Объект BaseParagraph |

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
