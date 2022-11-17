---
title: XFormCollection
second_title: Aspose.PDF для справки по Java API
description: Класс представляет коллекцию XFormCollection.
type: docs
weight: 408
url: /ru/java/com.aspose.pdf/xformcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class XFormCollection implements Iterable<XForm>
```

Класс представляет коллекцию XFormCollection.
## Методы

| Метод | Описание |
| --- | --- |
| [add(XForm xform)](#add-com.aspose.pdf.XForm-) | Добавляет новую XForm в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(XForm item)](#contains-com.aspose.pdf.XForm-) | Определяет, содержит ли коллекция определенное значение. |
| [copyTo(XForm[] array, int index)](#copyTo-com.aspose.pdf.XForm---int-) | Копирует XFormCollection в коллекцию. |
| [delete()](#delete--) | Удаляет все XForms из коллекции. |
| [delete(int index)](#delete-int-) | Удалить XForm из коллекции |
| [delete(String name)](#delete-java.lang.String-) | Удаляет XForm из коллекции по имени формы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormName(XForm form)](#getFormName-com.aspose.pdf.XForm-) | Возвращает имя формы в этой коллекции форм |
| [getSyncRoot()](#getSyncRoot--) | Объект синхронизации. |
| [get_Item(int index)](#get-Item-int-) | Возвращает XForm по индексу. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает XForm по его имени. |
| [hasForm(String formName)](#hasForm-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает true, если объект синхронизирован. |
| [iterator()](#iterator--) | Возвращает перечислитель коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XForm item)](#remove-com.aspose.pdf.XForm-) | Удаляет указанный элемент из коллекции. |
| [size()](#size--) | Получает количество XForms в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(XForm xform) {#add-com.aspose.pdf.XForm-}
```
public void add(XForm xform)
```


Добавляет новую XForm в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xform | [XForm](../../com.aspose.pdf/xform) | XForm для добавления в коллекцию |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### contains(XForm item) {#contains-com.aspose.pdf.XForm-}
```
public boolean contains(XForm item)
```


Определяет, содержит ли коллекция определенное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [XForm](../../com.aspose.pdf/xform) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - true, если элемент найден в коллекции; в противном случае ложно.
### copyTo(XForm[] array, int index) {#copyTo-com.aspose.pdf.XForm---int-}
```
public void copyTo(XForm[] array, int index)
```


Копирует XFormCollection в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [XForm\[\]](../../com.aspose.pdf/xform) | Массив XForm для копирования |
| index | int | Индекс, в который будет скопирован XFormCollection |

### delete() {#delete--}
```
public void delete()
```


Удаляет все XForms из коллекции.

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удалить XForm из коллекции

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс XForm, который необходимо удалить |

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Удаляет XForm из коллекции по имени формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя XForm для удаления. |

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
### getFormName(XForm form) {#getFormName-com.aspose.pdf.XForm-}
```
public String getFormName(XForm form)
```


Возвращает имя формы в этой коллекции форм

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | Форма, имя которой ищется |

**Возвращает:**
java.lang.String - Имя формы в коллекции; Null, если форма не содержится в коллекции
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Объект синхронизации.

**Возвращает:**
java.lang.Object — Объект
### get_Item(int index) {#get-Item-int-}
```
public XForm get_Item(int index)
```


Возвращает XForm по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс XFormCollection. Нумерация XForms начинается с 1 |

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - Восстановлен XForm
### get_Item(String name) {#get-Item-java.lang.String-}
```
public XForm get_Item(String name)
```


Возвращает XForm по его имени. Исключение выдается, если форма XForm с указанным именем не найдена.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя X-формы |

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - XForm объект
### hasForm(String formName) {#hasForm-java.lang.String-}
```
public boolean hasForm(String formName)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formName | java.lang.String |  |

**Возвращает:**
логический
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Возвращает true, если объект синхронизирован.

**Возвращает:**
логическое значение - логическое значение
### iterator() {#iterator--}
```
public Iterator<XForm> iterator()
```


Возвращает перечислитель коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.XForm> — перечислитель для коллекции
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XForm item) {#remove-com.aspose.pdf.XForm-}
```
public boolean remove(XForm item)
```


Удаляет указанный элемент из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [XForm](../../com.aspose.pdf/xform) | Объект для удаления |

**Возвращает:**
boolean - true, если элемент был удален из коллекции; в противном случае ложно.
### size() {#size--}
```
public int size()
```


Получает количество XForms в коллекции.

**Возвращает:**
интервал - целочисленное значение
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
