---
title: OptionCollection
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий набор опций поля выбора.
type: docs
weight: 238
url: /ru/java/com.aspose.pdf/optioncollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class OptionCollection implements Iterable<Option>
```

Класс, представляющий набор опций поля выбора.
## Методы

| Метод | Описание |
| --- | --- |
| [add(Option item)](#add-com.aspose.pdf.Option-) | Добавляет элемент в коллекцию, бросает . |
| [clear()](#clear--) | Удаляет все предметы из коллекции, выбрасывает . |
| [contains(Option item)](#contains-com.aspose.pdf.Option-) | Проверяет, существует ли элемент в коллекции, выдает . |
| [deleteOption(String name)](#deleteOption-java.lang.String-) | Удаляет опцию по ее имени. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Получает вариант по индексу. |
| [get(String name)](#get-java.lang.String-) | Получает вариант из коллекции по имени параметра. |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Объект синхронизации коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает вариант по индексу. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает вариант по его имени. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает истину о том, что объект синхронизирован. |
| [iterator()](#iterator--) | Возвращает перечислитель для параметров в коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Возвращает перечислитель для параметров в коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Option item)](#remove-com.aspose.pdf.Option-) | Удаляет предмет из коллекции, выбрасывает . |
| [size()](#size--) | Получает количество вариантов. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Option item) {#add-com.aspose.pdf.Option-}
```
public void add(Option item)
```


Добавляет элемент в коллекцию, бросает .

Еще не реализовано.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Option](../../com.aspose.pdf/option) | Экземпляр опции |

### clear() {#clear--}
```
public void clear()
```


Удаляет все предметы из коллекции, выбрасывает .

Еще не реализовано.

### contains(Option item) {#contains-com.aspose.pdf.Option-}
```
public boolean contains(Option item)
```


Проверяет, существует ли элемент в коллекции, выдает .

Еще не реализовано.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Option](../../com.aspose.pdf/option) | Экземпляр опции |

**Возвращает:**
boolean - логическое значение
### deleteOption(String name) {#deleteOption-java.lang.String-}
```
public void deleteOption(String name)
```


Удаляет опцию по ее имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя опции для удаления. |

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
### get(int index) {#get-int-}
```
public Option get(int index)
```


Получает вариант по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  Опционный индекс. Индекс должен быть в диапазоне[1..n], где n — количество вариантов. |

**Возвращает:**
[Option](../../com.aspose.pdf/option) - Восстановленный вариант.
### get(String name) {#get-java.lang.String-}
```
public Option get(String name)
```


Получает вариант из коллекции по имени параметра.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название опции. |

**Возвращает:**
[Option](../../com.aspose.pdf/option) - Восстановленный вариант.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Объект синхронизации коллекции.

**Возвращает:**
java.lang.Object — элемент объекта
### get_Item(int index) {#get-Item-int-}
```
public Option get_Item(int index)
```


Получает вариант по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс опции. |

**Возвращает:**
[Option](../../com.aspose.pdf/option) - Опцион на указанный индекс.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public Option get_Item(String name)
```


Получает вариант по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название опции. |

**Возвращает:**
[Option](../../com.aspose.pdf/option) - Найденный вариант.
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


Возвращает истину о том, что объект синхронизирован.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<Option> iterator()
```


Возвращает перечислитель для параметров в коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.Option> — перечислитель параметров.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


Возвращает перечислитель для параметров в коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator — перечислитель параметров.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Option item) {#remove-com.aspose.pdf.Option-}
```
public boolean remove(Option item)
```


Удаляет предмет из коллекции, выбрасывает .

Еще не реализовано.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Option](../../com.aspose.pdf/option) | Экземпляр опции |

**Возвращает:**
boolean - логическое значение
### size() {#size--}
```
public int size()
```


Получает количество вариантов.

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
