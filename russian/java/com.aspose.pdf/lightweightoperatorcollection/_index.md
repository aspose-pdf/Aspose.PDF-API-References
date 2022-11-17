---
title: LightweightOperatorCollection
second_title: Aspose.PDF для справки по Java API
description: Легкая коллекция оператора.
type: docs
weight: 194
url: /ru/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)
```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Легкая коллекция оператора. Предназначен для использования в сценариях, когда базовый поток содержимого не подключен, где в результате требуется только сбор данных оператором.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LightweightOperatorCollection()](#LightweightOperatorCollection--) | Инициализировать объект |
| [LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators)](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | Только для внутреннего использования! |
| [LightweightOperatorCollection(OperatorCollection operatorCollection)](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Инициализировать объект |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Добавить оператора |
| [addRange(LightweightOperatorCollection oc)](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Добавить коллекцию LightweightOperatorCollection |
| [cancelUpdate()](#cancelUpdate--) | Отменяет последнее обновление. |
| [clear()](#clear--) |  |
| [contains(Operator item)](#contains-com.aspose.pdf.Operator-) |  |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | внутреннее удаление Unrestrictedelement |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Для внутреннего использования оператор getUnrestricted |
| [get_Item(int index)](#get-Item-int-) | Получает оператор по его индексу. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Вставить оператор |
| [isEmpty()](#isEmpty--) | Возвращает TRUE, если коллекция пуста. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Указывает, ограничена ли коллекция быстрым извлечением текста |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [iterator()](#iterator--) | Итератор возврата |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator item)](#remove-com.aspose.pdf.Operator-) |  |
| [resumeUpdate()](#resumeUpdate--) | Возобновление обновления документа. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Устанавливает оператор по его индексу. |
| [size()](#size--) | Количество операторов |
| [suppressUpdate()](#suppressUpdate--) | Подавляет обновление содержимого данных. |
| [toList()](#toList--) | Возвращает список операторов. |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | внутренний |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LightweightOperatorCollection() {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```


Инициализировать объект

### LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators) {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators)
```


Только для внутреннего использования!

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | Внутренний объект |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> | Внутренний объект |

### LightweightOperatorCollection(OperatorCollection operatorCollection) {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
```
public LightweightOperatorCollection(OperatorCollection operatorCollection)
```


Инициализировать объект

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorCollection | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | Объект OperatorCollection |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public void add(Operator op)
```


Добавить оператора

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Объект оператора |

### addRange(LightweightOperatorCollection oc) {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
```
public void addRange(LightweightOperatorCollection oc)
```


Добавить коллекцию LightweightOperatorCollection

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| oc | [LightweightOperatorCollection](../../com.aspose.pdf/lightweightoperatorcollection) | Экземпляр LightweightOperatorCollection |

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


Отменяет последнее обновление. Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого.

### clear() {#clear--}
```
public void clear()
```


Очищает коллекцию.

### contains(Operator item) {#contains-com.aspose.pdf.Operator-}
```
public boolean contains(Operator item)
```


Проверьте, находится ли предмет в коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Экземпляр оператора |

**Возвращает:**
boolean - логическое значение
### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


внутреннее удаление Unrestrictedelement

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |

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
### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```


Для внутреннего использования оператор getUnrestricted

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |

**Возвращает:**
[Operator](../../com.aspose.pdf/operator) - Объект оператора
### get_Item(int index) {#get-Item-int-}
```
public Operator get_Item(int index)
```


Получает оператор по его индексу.

--------------------

```
Example demonstrates how to get operator of page contents by index.


 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get_Item(1).getContents();
 Operator first = oc.get_Item(1);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. Нумерация начинается с 1. |

**Возвращает:**
[Operator](../../com.aspose.pdf/operator) - Оператор из запрошенного индекса
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public void insert(int index, Operator op)
```


Вставить оператор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |
| op | [Operator](../../com.aspose.pdf/operator) | Объект оператора |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает TRUE, если коллекция пуста.

**Возвращает:**
boolean - логическое значение
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


Указывает, ограничена ли коллекция быстрым извлечением текста

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
логический
### iterator() {#iterator--}
```
public Iterator<Operator> iterator()
```


Итератор возврата

**Возвращает:**
java.util.Iterator<com.aspose.pdf.Operator> — объект IGenericEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Operator item) {#remove-com.aspose.pdf.Operator-}
```
public boolean remove(Operator item)
```


Удаляет оператора из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Экземпляр оператора |

**Возвращает:**
boolean - логическое значение
### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


Возобновление обновления документа. Обновляет поток содержимого, если есть какие-либо ожидающие изменения.

### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public void set_Item(int index, Operator value)
```


Устанавливает оператор по его индексу.

--------------------

```
Example demonstrates how to get operator of page contents by index.


 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get_Item(1).getContents();
 Operator first = oc.get_Item(1);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. Нумерация начинается с 1. |
| value | [Operator](../../com.aspose.pdf/operator) | Оператор из запрошенного индекса |

### size() {#size--}
```
public int size()
```


Количество операторов

**Возвращает:**
интервал - целочисленное значение
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Подавляет обновление содержимого данных. Поток содержимого не обновляется до тех пор, пока не будет вызвана функция ResumeUpdate.

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


Возвращает список операторов.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - список операторов.
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### updateData() {#updateData--}
```
public void updateData()
```


внутренний

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
