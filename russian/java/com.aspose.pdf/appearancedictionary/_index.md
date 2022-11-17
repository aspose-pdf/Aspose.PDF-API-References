---
title: AppearanceDictionary
second_title: Aspose.PDF для справки по Java API
description: Словарь внешнего вида аннотации, указывающий, как аннотация должна быть визуально представлена на странице.
type: docs
weight: 24
url: /ru/java/com.aspose.pdf/appearancedictionary/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class AppearanceDictionary implements System.Collections.Generic.IGenericDictionary<String,XForm>
```

Словарь внешнего вида аннотации, указывающий, как аннотация должна быть визуально представлена на странице.
## Методы

| Метод | Описание |
| --- | --- |
| [add(Object key, Object value)](#add-java.lang.Object-java.lang.Object-) | Добавляет элемент с предоставленным ключом и значением. |
| [addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Добавляет пару с ключом и значением в словарь. |
| [addItem(String key, XForm value)](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Добавить форму X для указанного ключа. |
| [clear()](#clear--) | Удаляет все элементы из словаря. |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Проверяет, содержится ли указанная пара ключ-значение в словаре. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Определяет, содержит ли этот словарь указанный ключ. |
| [copyTo(XForm[] array, int index)](#copyTo-com.aspose.pdf.XForm---int-) | Копирует элементы словаря в массив, начиная с определенного индекса массива. |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm----int-) | Копирует элементы коллекции ICollection в массив, начиная с определенного индекса массива. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDict()](#getDict--) | Получает pdf словарь |
| [getKeys()](#getKeys--) | Получает ключи словаря. |
| [getKeys_()](#getKeys---) | Получает ключи словаря. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к словарю. |
| [getValues()](#getValues--) | Получает список значений словаря. |
| [getValues_()](#getValues---) | Получает список значений словаря. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Представляет собой удобную форму для получения потоков появления. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | Получает значение, указывающее, имеет ли словарь фиксированный размер. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступен ли словарь только для чтения. |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к словарю синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает объект IDictionaryEnumerator для словаря. |
| [iterator__Rename_Namesake()](#iterator--Rename-Namesake--) | Нумератор для коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Удаляет пару ключ/значение из коллекции. |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | Удаляет ключ из словаря. |
| [set_Item(String key, XForm value)](#set-Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size()](#size--) | Получает количество элементов, содержащихся в словаре. |
| [toString()](#toString--) |  |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Пытается найти ключ в словаре и извлекает значение, если оно найдено. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object key, Object value) {#add-java.lang.Object-java.lang.Object-}
```
public void add(Object key, Object value)
```


Добавляет элемент с предоставленным ключом и значением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.Object | Ключ элемента. |
| value | java.lang.Object | Значение элемента. |

### addItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


Добавляет пару с ключом и значением в словарь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | Товар, который нужно добавить. |

### addItem(String key, XForm value) {#addItem-java.lang.String-com.aspose.pdf.XForm-}
```
public void addItem(String key, XForm value)
```


Добавить форму X для указанного ключа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ элемента. |
| value | [XForm](../../com.aspose.pdf/xform) | Значение объекта XForm. |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из словаря.

### containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


Проверяет, содержится ли указанная пара ключ-значение в словаре.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | Пара ключ-значение. |

**Возвращает:**
boolean - true, если этот файл был найден.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Определяет, содержит ли этот словарь указанный ключ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для поиска в словаре. |

**Возвращает:**
boolean - истина, если ключ найден.
### copyTo(XForm[] array, int index) {#copyTo-com.aspose.pdf.XForm---int-}
```
public void copyTo(XForm[] array, int index)
```


Копирует элементы словаря в массив, начиная с определенного индекса массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [XForm\[\]](../../com.aspose.pdf/xform) | Массив, в который необходимо скопировать элементы. |
| index | int | Индекс, куда элементы должны быть скопированы. |

### copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex)
```


Копирует элементы коллекции ICollection в массив, начиная с определенного индекса массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>[] | Одномерный массив, который является местом назначения элементов, скопированных из ICollection. Массив должен иметь индексацию с отсчетом от нуля. |
| arrayIndex | int | Отсчитываемый от нуля индекс в массиве, с которого начинается копирование. |

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
### getDict() {#getDict--}
```
public IPdfDictionary getDict()
```


Получает pdf словарь

**Возвращает:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - Объект IPdfDictionary
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


Получает ключи словаря. Если словарь внешнего вида имеет подчиненные слова, то Keys содержит (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> — список строковых значений
### getKeys_() {#getKeys---}
```
public List<String> getKeys_()
```


Получает ключи словаря. Если словарь внешнего вида имеет подчиненные слова, то Keys содержит (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**Возвращает:**
java.util.List<java.lang.String> — Список строковых значений
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который можно использовать для синхронизации доступа к словарю.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XForm> getValues()
```


Получает список значений словаря. Коллекция результатов содержит список объектов XForm.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XForm> — Список значений XForm
### getValues_() {#getValues---}
```
public List<XForm> getValues_()
```


Получает список значений словаря. Коллекция результатов содержит список объектов XForm.

**Возвращает:**
java.util.List<com.aspose.pdf.XForm> — Список значений XForm
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XForm get_Item(String key)
```


Представляет собой удобную форму для получения потоков появления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Представляет путь к потоку внешнего вида. Если словарь внешнего вида имеет подсловари, то путь должен состоять из 2 частей ( Ключи ), иначе путь состоит только из одной части. |

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - Объект XForm (поток внешнего вида), который соответствует данному ключу.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```


Получает значение, указывающее, имеет ли словарь фиксированный размер.

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступен ли словарь только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Получает значение, указывающее, является ли доступ к словарю синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator()
```


Возвращает объект IDictionaryEnumerator для словаря.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> — перечислитель словаря.
### iterator__Rename_Namesake() {#iterator--Rename-Namesake--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator__Rename_Namesake()
```


Нумератор для коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> - перечислитель элементов коллекции.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


Удаляет пару ключ/значение из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | Пара ключ/значение, которую нужно удалить. |

**Возвращает:**
boolean - true, если пара была найдена и удалена.
### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


Удаляет ключ из словаря.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, который нужно удалить из словаря. |

**Возвращает:**
boolean - true, если ключ был успешно удален.
### set_Item(String key, XForm value) {#set-Item-java.lang.String-com.aspose.pdf.XForm-}
```
public void set_Item(String key, XForm value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String |  |
| value | [XForm](../../com.aspose.pdf/xform) |  |

### size() {#size--}
```
public int size()
```


Получает количество элементов, содержащихся в словаре.

**Возвращает:**
интервал - целочисленное значение
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public boolean tryGetValue(String key, Object[] value)
```


Пытается найти ключ в словаре и извлекает значение, если оно найдено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для поиска в словаре. |
| value | java.lang.Object[] | Полученное значение. |

**Возвращает:**
boolean - истина, если ключ найден.
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
