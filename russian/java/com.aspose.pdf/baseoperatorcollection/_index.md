---
title: BaseOperatorCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет базовый класс для коллекции операторов.
type: docs
weight: 33
url: /ru/java/com.aspose.pdf/baseoperatorcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public abstract class BaseOperatorCollection implements Iterable<Operator>
```

Представляет базовый класс для коллекции операторов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BaseOperatorCollection()](#BaseOperatorCollection--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Добавляет новый оператор в коллекцию. |
| [cancelUpdate()](#cancelUpdate--) | Отменяет последнее обновление. |
| [clear()](#clear--) | Очищает коллекцию. |
| [contains(Operator item)](#contains-com.aspose.pdf.Operator-) | Проверьте, находится ли предмет в коллекции. |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | внутренний |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Только для внутреннего использования |
| [get_Item(int index)](#get-Item-int-) | Получает оператор по его индексу. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Вставляет оператор в коллекцию. |
| [isEmpty()](#isEmpty--) | Возвращает TRUE, если коллекция пуста. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Указывает, ограничена ли коллекция быстрым извлечением текста |
| [isReadOnly()](#isReadOnly--) | Возвращает true, если коллекция доступна только для чтения. |
| [iterator()](#iterator--) | Возвращает перечислитель для коллекции |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator item)](#remove-com.aspose.pdf.Operator-) | Удаляет оператора из коллекции. |
| [resumeUpdate()](#resumeUpdate--) | Возобновление обновления документа. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Устанавливает оператор по его индексу. |
| [size()](#size--) | Получает количество операторов в коллекции. |
| [suppressUpdate()](#suppressUpdate--) | Подавляет обновление содержимого данных. |
| [toList()](#toList--) | Возвращает список операторов. |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | внутренний |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseOperatorCollection() {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```


### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public abstract void add(Operator op)
```


Добавляет новый оператор в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Оператор, который необходимо добавить |

### cancelUpdate() {#cancelUpdate--}
```
public abstract void cancelUpdate()
```


Отменяет последнее обновление. Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого.

### clear() {#clear--}
```
public abstract void clear()
```


Очищает коллекцию.

### contains(Operator item) {#contains-com.aspose.pdf.Operator-}
```
public abstract boolean contains(Operator item)
```


Проверьте, находится ли предмет в коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Элемент экземпляра оператора, который нужно найти. |

**Возвращает:**
boolean - логическое значение True - если элемент найден; в противном случае ложно.
### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```


внутренний

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
public abstract Operator getUnrestricted(int index)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |

**Возвращает:**
[Operator](../../com.aspose.pdf/operator) - Объект оператора
### get_Item(int index) {#get-Item-int-}
```
public abstract Operator get_Item(int index)
```


Получает оператор по его индексу.

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
public abstract void insert(int index, Operator op)
```


Вставляет оператор в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, в который необходимо добавить новый оператор |
| op | [Operator](../../com.aspose.pdf/operator) | Оператор, который будет вставлен |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает TRUE, если коллекция пуста.

**Возвращает:**
boolean - логическое значение
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```


Указывает, ограничена ли коллекция быстрым извлечением текста

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public abstract boolean isReadOnly()
```


Возвращает true, если коллекция доступна только для чтения.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public abstract Iterator<Operator> iterator()
```


Возвращает перечислитель для коллекции

**Возвращает:**
java.util.Iterator<com.aspose.pdf.Operator> — перечислитель коллекций
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
public abstract boolean remove(Operator item)
```


Удаляет оператора из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Элемент экземпляра оператора для удаления. |

**Возвращает:**
boolean - логическое значение True - если элемент удален; в противном случае ложно.
### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```


Возобновление обновления документа. Обновляет поток содержимого, если есть какие-либо ожидающие изменения.

### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public abstract void set_Item(int index, Operator value)
```


Устанавливает оператор по его индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. Нумерация начинается с 1. |
| value | [Operator](../../com.aspose.pdf/operator) | Оператор. |

### size() {#size--}
```
public abstract int size()
```


Получает количество операторов в коллекции.

**Возвращает:**
int - целочисленное значение
### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```


Подавляет обновление содержимого данных. Поток содержимого не обновляется до тех пор, пока не будет вызвана функция ResumeUpdate.

### toList() {#toList--}
```
public abstract System.Collections.Generic.List<Operator> toList()
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
public abstract void updateData()
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
