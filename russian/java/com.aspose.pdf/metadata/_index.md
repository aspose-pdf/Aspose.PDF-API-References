---
title: Metadata
second_title: Aspose.PDF для справки по Java API
description: Предоставляет доступ к потоку метаданных XMP.
type: docs
weight: 220
url: /ru/java/com.aspose.pdf/metadata/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class Metadata implements System.Collections.Generic.IGenericDictionary<String,XmpValue>
```

Предоставляет доступ к потоку метаданных XMP.
## Методы

| Метод | Описание |
| --- | --- |
| [addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Добавляет пару с ключом и значением в словарь. |
| [addItem(String prefix, XmpPdfAExtensionObject value)](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Добавляет расширение pdf к метаданным. |
| [addItem(String key, XmpValue value)](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Добавляет ценность метаданным. |
| [addItem(String key, Object value)](#addItem-java.lang.String-java.lang.Object-) | Добавляет ценность метаданным. |
| [clear()](#clear--) | Очищает метаданные. |
| [contains(String key)](#contains-java.lang.String-) | Проверяет, содержится ли ключ в метаданных. |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Проверяет, содержится ли указанная пара ключ-значение в словаре. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Определяет, содержит ли этот словарь указанный ключ. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует элементы коллекции в массив. |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-) | Копирует элементы коллекции в массив. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtensionFields()](#getExtensionFields--) | Получает словарь полей расширения. |
| [getExtensionFields_Internal()](#getExtensionFields-Internal--) | Только для внутреннего использования. |
| [getKeys()](#getKeys--) | Получает коллекцию ключей метаданных. |
| [getNamespaceUriByPrefix(String prefix)](#getNamespaceUriByPrefix-java.lang.String-) | Возвращает URI пространства имен по префиксу. |
| [getPrefixByNamespaceUri(String namespaceUri)](#getPrefixByNamespaceUri-java.lang.String-) | Возвращает префикс по URI пространства имен. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект синхронизации коллекции. |
| [getValues()](#getValues--) | Получает значения в метаданных. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Получает данные из метаданных. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | Проверяет, имеет ли коллекция фиксированный размер. |
| [isReadOnly()](#isReadOnly--) | Проверяет, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Проверяет, синхронизирована ли коллекция. |
| [iterator()](#iterator--) | Возвращает перечислитель словаря. |
| [iteratorIE()](#iteratorIE--) | Получает перечислитель коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Регистрирует URI пространства имен. |
| [registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription)](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Регистрирует URI пространства имен. |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Удаляет пару ключ/значение из коллекции. |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | Удаляет запись из метаданных. |
| [set_Item(String key, XmpValue value)](#set-Item-java.lang.String-com.aspose.pdf.XmpValue-) | Устанавливает данные из метаданных. |
| [size()](#size--) | Получает количество элементов в коллекции. |
| [toString()](#toString--) |  |
| [tryGetValue(String key, XmpValue[] value)](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue---) | Пытается найти ключ в словаре и извлекает значение, если оно найдено. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Пытается найти ключ в словаре и извлекает значение, если оно найдено. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Добавляет пару с ключом и значением в словарь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Товар, который нужно добавить. |

### addItem(String prefix, XmpPdfAExtensionObject value) {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void addItem(String prefix, XmpPdfAExtensionObject value)
```


Добавляет расширение pdf к метаданным.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | java.lang.String | Префикс расширения. |
| value | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | Значение, которое будет добавлено. |

### addItem(String key, XmpValue value) {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void addItem(String key, XmpValue value)
```


Добавляет ценность метаданным.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для добавления. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Значение, которое будет добавлено. |

### addItem(String key, Object value) {#addItem-java.lang.String-java.lang.Object-}
```
public void addItem(String key, Object value)
```


Добавляет ценность метаданным.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для добавления. |
| value | java.lang.Object | Значение, которое будет добавлено. |

### clear() {#clear--}
```
public void clear()
```


Очищает метаданные.

### contains(String key) {#contains-java.lang.String-}
```
public boolean contains(String key)
```


Проверяет, содержится ли ключ в метаданных.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ входа найти. |

**Возвращает:**
boolean — Истинно, если ключ содержится в метаданных.
### containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Проверяет, содержится ли указанная пара ключ-значение в словаре.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Пара ключ-значение. |

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
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Копирует элементы коллекции в массив.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс. |

### copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)
```


Копирует элементы коллекции в массив.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] | Целевой массив. |
| index | int | Начальный индекс. |

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
### getExtensionFields() {#getExtensionFields--}
```
public Hashtable<String,XmpPdfAExtensionSchema> getExtensionFields()
```


Получает словарь полей расширения.

**Возвращает:**
java.util.Hashtable<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> — объект Hashtable
### getExtensionFields_Internal() {#getExtensionFields-Internal--}
```
public System.Collections.Generic.IGenericDictionary<String,XmpPdfAExtensionSchema> getExtensionFields_Internal()
```


Только для внутреннего использования.

Получает словарь полей расширения.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> — внутренний объект
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


Получает коллекцию ключей метаданных.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> — объект ICollection
### getNamespaceUriByPrefix(String prefix) {#getNamespaceUriByPrefix-java.lang.String-}
```
public String getNamespaceUriByPrefix(String prefix)
```


Возвращает URI пространства имен по префиксу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | java.lang.String | Значение префикса. |

**Возвращает:**
java.lang.String — значение URI пространства имен.
### getPrefixByNamespaceUri(String namespaceUri) {#getPrefixByNamespaceUri-java.lang.String-}
```
public String getPrefixByNamespaceUri(String namespaceUri)
```


Возвращает префикс по URI пространства имен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI пространства имен. |

**Возвращает:**
java.lang.String — значение префикса.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект синхронизации коллекции.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XmpValue> getValues()
```


Получает значения в метаданных.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XmpValue> — объект ICollection
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XmpValue get_Item(String key)
```


Получает данные из метаданных.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключевое имя. |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Объект метаданных.
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


Проверяет, имеет ли коллекция фиксированный размер.

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Проверяет, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Проверяет, синхронизирована ли коллекция.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iterator()
```


Возвращает перечислитель словаря.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> — перечислитель.
### iteratorIE() {#iteratorIE--}
```
public Iterator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iteratorIE()
```


Получает перечислитель коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> — объект IEnumerator
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
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




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Регистрирует URI пространства имен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | java.lang.String | Значение префикса. |
| namespaceUri | java.lang.String | Значение URI пространства имен. |

### registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription) {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription)
```


Регистрирует URI пространства имен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | java.lang.String | Значение префикса. |
| namespaceUri | java.lang.String | Значение URI пространства имен. |
| schemaDescription | java.lang.String | Значение описания схемы. |

### removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Удаляет пару ключ/значение из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Пара ключ/значение, которую нужно удалить. |

**Возвращает:**
boolean - true, если пара была найдена и удалена.
### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


Удаляет запись из метаданных.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ входа удалить. |

**Возвращает:**
boolean - True - если ключ удален; в противном случае ложно.
### set_Item(String key, XmpValue value) {#set-Item-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void set_Item(String key, XmpValue value)
```


Устанавливает данные из метаданных.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | имя ключа |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Объект значения |

### size() {#size--}
```
public int size()
```


Получает количество элементов в коллекции.

**Возвращает:**
интервал - целочисленное значение
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### tryGetValue(String key, XmpValue[] value) {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue---}
```
public boolean tryGetValue(String key, XmpValue[] value)
```


Пытается найти ключ в словаре и извлекает значение, если оно найдено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для поиска в словаре. |
| value | [XmpValue\[\]](../../com.aspose.pdf/xmpvalue) | Полученное значение. |

**Возвращает:**
boolean - истина, если ключ найден.
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
