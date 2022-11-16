---
title: DocumentInfo
second_title: Aspose.PDF для справки по Java API
description: Представляет метаинформацию документа PDF.
type: docs
weight: 94
url: /ru/java/com.aspose.pdf/documentinfo/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary
```
public final class DocumentInfo extends System.Collections.Generic.Dictionary<String,String>
```

Представляет метаинформацию документа PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DocumentInfo(IDocument document)](#DocumentInfo-com.aspose.pdf.IDocument-) | Инициализировать экземпляр DocumentInfo. |
## Методы

| Метод | Описание |
| --- | --- |
| [addItem(TKey arg0, TValue arg1)](#addItem-TKey-TValue-) |  |
| [addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [addItem(String key, String value)](#addItem-java.lang.String-java.lang.String-) | Добавляет в коллекцию элемент с указанными ключом и значением. |
| [clear()](#clear--) | Очищает информацию о документе. |
| [clearCustomData()](#clearCustomData--) | Очищает только пользовательские данные, оставляет все остальные предопределенные значения (название, автор и т. д.). |
| [containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [containsKey(TKey arg0)](#containsKey-TKey-) |  |
| [containsValue(TValue arg0)](#containsValue-TValue-) |  |
| [copyTo(System.Array arg0, int arg1)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue----int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthor()](#getAuthor--) | Получает автора документа. |
| [getClass()](#getClass--) |  |
| [getComparer()](#getComparer--) |  |
| [getCreationDate()](#getCreationDate--) | Получает дату создания документа. |
| [getCreationTimeZone()](#getCreationTimeZone--) | Часовой пояс даты создания в миллисекундах. |
| [getCreator()](#getCreator--) | Получает создателя документа. |
| [getDictionaryEntryEnumerator()](#getDictionaryEntryEnumerator--) |  |
| [getKeys()](#getKeys--) |  |
| [getKeywords()](#getKeywords--) | Получает ключевые слова документа. |
| [getModDate()](#getModDate--) | Получает дату модификации документа. |
| [getModTimeZone()](#getModTimeZone--) | Часовой пояс даты изменения. |
| [getProducer()](#getProducer--) | Получает производителя документа. |
| [getSubject()](#getSubject--) | Получает тему документа. |
| [getSyncRoot()](#getSyncRoot--) |  |
| [getTitle()](#getTitle--) | Получает заголовок документа. |
| [getTrapped()](#getTrapped--) | Получает захваченный флаг. |
| [getValues()](#getValues--) |  |
| [get_Item(TKey arg0)](#get-Item-TKey-) |  |
| [get_Item(String key)](#get-Item-java.lang.String-) | Получает значение, связанное с указанным ключом. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) |  |
| [isPredefinedKey(String key)](#isPredefinedKey-java.lang.String-) | Определяет, является ли ключ предопределенным (название, автор и т. д.), а не настраиваемым. |
| [isReadOnly()](#isReadOnly--) |  |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Удаляет элемент с указанным ключом из коллекции. |
| [removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [removeItemByKey(TKey arg0)](#removeItemByKey-TKey-) |  |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Устанавливает автора документа. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Устанавливает дату создания документа. |
| [setCreationTimeZone(double value)](#setCreationTimeZone-double-) | Часовой пояс даты создания в миллисекундах. |
| [setCreator(String value)](#setCreator-java.lang.String-) | Устанавливает создателя документа. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Установите ключевые слова документа. |
| [setModDate(Date value)](#setModDate-java.util.Date-) | Устанавливает дату модификации документа. |
| [setModTimeZone(double value)](#setModTimeZone-double-) | Часовой пояс даты изменения. |
| [setProducer(String value)](#setProducer-java.lang.String-) | Устанавливает производителя документа. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Устанавливает тему документа. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Устанавливает заголовок документа. |
| [setTrapped(String value)](#setTrapped-java.lang.String-) | Устанавливает захваченный флаг. |
| [set_Item(TKey arg0, TValue arg1)](#set-Item-TKey-TValue-) |  |
| [set_Item(String key, String value)](#set-Item-java.lang.String-java.lang.String-) | Задает значение, связанное с указанным ключом. |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [tryGetValue(TKey arg0, Object[] arg1)](#tryGetValue-TKey-java.lang.Object---) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentInfo(IDocument document) {#DocumentInfo-com.aspose.pdf.IDocument-}
```
public DocumentInfo(IDocument document)
```


Инициализировать экземпляр DocumentInfo.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Информация этого документа будет использоваться для инициализации. |

### addItem(TKey arg0, TValue arg1) {#addItem-TKey-TValue-}
```
public void addItem(TKey arg0, TValue arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | TValue |  |

### addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

### addItem(String key, String value) {#addItem-java.lang.String-java.lang.String-}
```
public void addItem(String key, String value)
```


Добавляет в коллекцию элемент с указанными ключом и значением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ добавляемого элемента. |
| value | java.lang.String | Значение добавляемого элемента. Значение может быть нулевым. |

### clear() {#clear--}
```
public void clear()
```


Очищает информацию о документе.

### clearCustomData() {#clearCustomData--}
```
public void clearCustomData()
```


Очищает только пользовательские данные, оставляет все остальные предопределенные значения (название, автор и т. д.).

### containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

**Возвращает:**
логический
### containsKey(TKey arg0) {#containsKey-TKey-}
```
public boolean containsKey(TKey arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | TKey |  |

**Возвращает:**
логический
### containsValue(TValue arg0) {#containsValue-TValue-}
```
public boolean containsValue(TValue arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | TValue |  |

**Возвращает:**
логический
### copyTo(System.Array arg0, int arg1) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Array |  |
| arg1 | int |  |

### copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue>[] |  |
| arg1 | int |  |

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
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Получает автора документа.

**Возвращает:**
java.lang.String — строковое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getComparer() {#getComparer--}
```
public System.Collections.Generic.IGenericEqualityComparer<TKey> getComparer()
```




**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEqualityComparer<TKey>
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Получает дату создания документа.

**Возвращает:**
[Date](../../java.util/date) - Объект даты
### getCreationTimeZone() {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```


Часовой пояс даты создания в миллисекундах.

**Возвращает:**
двойное - двойное значение
### getCreator() {#getCreator--}
```
public String getCreator()
```


Получает создателя документа.

**Возвращает:**
java.lang.String — строковое значение
### getDictionaryEntryEnumerator() {#getDictionaryEntryEnumerator--}
```
public System.Collections.IEnumerable<System.Collections.DictionaryEntry> getDictionaryEntryEnumerator()
```




**Возвращает:**
com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.DictionaryEntry>
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<TKey,TValue> getKeys()
```




**Возвращает:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<TKey,TValue>
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Получает ключевые слова документа.

**Возвращает:**
java.lang.String — строковое значение
### getModDate() {#getModDate--}
```
public Date getModDate()
```


Получает дату модификации документа.

**Возвращает:**
[Date](../../java.util/date) - Объект даты
### getModTimeZone() {#getModTimeZone--}
```
public double getModTimeZone()
```


Часовой пояс даты изменения.

**Возвращает:**
двойное - двойное значение
### getProducer() {#getProducer--}
```
public String getProducer()
```


Получает производителя документа.

**Возвращает:**
java.lang.String — строковое значение
### getSubject() {#getSubject--}
```
public String getSubject()
```


Получает тему документа.

**Возвращает:**
java.lang.String — строковое значение
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Возвращает:**
java.lang.Объект
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает заголовок документа.

**Возвращает:**
java.lang.String — строковое значение
### getTrapped() {#getTrapped--}
```
public String getTrapped()
```


Получает захваченный флаг.

**Возвращает:**
java.lang.String — строковое значение
### getValues() {#getValues--}
```
public System.Collections.Generic.Dictionary.ValueCollection<TKey,TValue> getValues()
```




**Возвращает:**
com.aspose.ms.System.Collections.Generic.Dictionary.ValueCollection<TKey,TValue>
### get_Item(TKey arg0) {#get-Item-TKey-}
```
public TValue get_Item(TKey arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | TKey |  |

**Возвращает:**
Tзначение
### get_Item(String key) {#get-Item-java.lang.String-}
```
public String get_Item(String key)
```


Получает значение, связанное с указанным ключом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, значение которого нужно получить или установить. |

**Возвращает:**
java.lang.String — объект значения
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




**Возвращает:**
логический
### isPredefinedKey(String key) {#isPredefinedKey-java.lang.String-}
```
public static boolean isPredefinedKey(String key)
```


Определяет, является ли ключ предопределенным (название, автор и т. д.), а не настраиваемым.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Выбранный ключ |

**Возвращает:**
boolean — Истинно, если ключ предопределен.
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Возвращает:**
логический
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```




**Возвращает:**
логический
### iterator() {#iterator--}
```
public System.Collections.Generic.Dictionary.Enumerator<TKey,TValue> iterator()
```




**Возвращает:**
com.aspose.ms.System.Collections.Generic.Dictionary.Enumerator<TKey,TValue>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public void remove(String key)
```


Удаляет элемент с указанным ключом из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ удаляемого элемента. |

### removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

**Возвращает:**
логический
### removeItemByKey(TKey arg0) {#removeItemByKey-TKey-}
```
public boolean removeItemByKey(TKey arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | TKey |  |

**Возвращает:**
логический
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Устанавливает автора документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Устанавливает дату создания документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Объект даты |

### setCreationTimeZone(double value) {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```


Часовой пояс даты создания в миллисекундах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | в миллисекундах |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


Устанавливает создателя документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Установите ключевые слова документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


Устанавливает дату модификации документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Объект даты |

### setModTimeZone(double value) {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```


Часовой пояс даты изменения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setProducer(String value) {#setProducer-java.lang.String-}
```
public void setProducer(String value)
```


Устанавливает производителя документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Устанавливает тему документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Устанавливает заголовок документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTrapped(String value) {#setTrapped-java.lang.String-}
```
public void setTrapped(String value)
```


Устанавливает захваченный флаг.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### set_Item(TKey arg0, TValue arg1) {#set-Item-TKey-TValue-}
```
public void set_Item(TKey arg0, TValue arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | TValue |  |

### set_Item(String key, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public void set_Item(String key, String value)
```


Задает значение, связанное с указанным ключом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковый объект |
| value | java.lang.String | Объект |

### size() {#size--}
```
public int size()
```




**Возвращает:**
инт
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### tryGetValue(TKey arg0, Object[] arg1) {#tryGetValue-TKey-java.lang.Object---}
```
public boolean tryGetValue(TKey arg0, Object[] arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | java.lang.Object[] |  |

**Возвращает:**
логический
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
