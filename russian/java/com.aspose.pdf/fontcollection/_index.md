---
title: FontCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет коллекцию шрифтов.
type: docs
weight: 132
url: /ru/java/com.aspose.pdf/fontcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class FontCollection implements Iterable<Font>
```

Представляет коллекцию шрифтов.

--------------------

```
The example demonstrates how to make all font declared on page as embedded.


 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // убедитесь, что все шрифты, объявленные на ресурсах страницы, встроены
 //обратите внимание, что если шрифты объявлены в ресурсах формы, они недоступны из ресурсов страницы.
 for(com.aspsoe.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts())
 {
     if(!font.isEmbedded())
         font.isEmbedded(true);
 }
 doc.save("D:\\Tests\\input.pdf");
```

--------------------

Коллекции шрифтов, представленные классом FontCollection, используются в нескольких сценариях. Например, в ресурсах со свойством Resources.Fonts.
## Методы

| Метод | Описание |
| --- | --- |
| [add(Font fragment)](#add-com.aspose.pdf.Font-) | Добавляет шрифт в коллекцию. |
| [add(Font newFont, String[] resName)](#add-com.aspose.pdf.Font-java.lang.String---) | Добавляет новый шрифт в ресурсы шрифта и возвращает автоматически назначенное имя ресурса шрифта. |
| [add(String resName, IPdfObject newFont)](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Добавить новый шрифт в коллекцию шрифтов. |
| [add(String resName, String baseFontName)](#add-java.lang.String-java.lang.String-) | Добавляет в ресурсы шрифта новую запись шрифта с указанным базовым именем шрифта. |
| [clear_Rename_Namesake()](#clear-Rename-Namesake--) | Удаляет все элементы из коллекции. |
| [contains(Font item)](#contains-com.aspose.pdf.Font-) | Определяет, содержит ли коллекция определенное значение. |
| [contains(String name)](#contains-java.lang.String-) | Проверяет, существует ли шрифт в коллекции шрифтов. |
| [copyTo(Font[] array, int index)](#copyTo-com.aspose.pdf.Font---int-) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHash()](#getHash--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент шрифта по указанному индексу. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает шрифт из коллекции по имени шрифта. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель для всей коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Возвращает перечислитель для всей коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Font item)](#remove-com.aspose.pdf.Font-) | Удаляет указанный элемент из коллекции. |
| [size()](#size--) | Получает количество элементов объекта Font, фактически содержащихся в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Font fragment) {#add-com.aspose.pdf.Font-}
```
public void add(Font fragment)
```


Добавляет шрифт в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fragment | [Font](../../com.aspose.pdf/font) | Объект шрифта |

### add(Font newFont, String[] resName) {#add-com.aspose.pdf.Font-java.lang.String---}
```
public void add(Font newFont, String[] resName)
```


Добавляет новый шрифт в ресурсы шрифта и возвращает автоматически назначенное имя ресурса шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| newFont | [Font](../../com.aspose.pdf/font) | Объект шрифта. |
| resName | java.lang.String[] | Автоматически назначаемое имя элемента ресурса. |

### add(String resName, IPdfObject newFont) {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
```
public void add(String resName, IPdfObject newFont)
```


Добавить новый шрифт в коллекцию шрифтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resName | java.lang.String | Строковый объект |
| newFont | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | Объект IPdfObject |

### add(String resName, String baseFontName) {#add-java.lang.String-java.lang.String-}
```
public void add(String resName, String baseFontName)
```


Добавляет в ресурсы шрифта новую запись шрифта с указанным базовым именем шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resName | java.lang.String | Строковый объект |
| baseFontName | java.lang.String | Строковый объект |

### clear_Rename_Namesake() {#clear-Rename-Namesake--}
```
public void clear_Rename_Namesake()
```


Удаляет все элементы из коллекции.

### contains(Font item) {#contains-com.aspose.pdf.Font-}
```
public boolean contains(Font item)
```


Определяет, содержит ли коллекция определенное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Font](../../com.aspose.pdf/font) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - true, если элемент найден в коллекции; в противном случае ложно.
### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


Проверяет, существует ли шрифт в коллекции шрифтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название шрифта. |

**Возвращает:**
boolean - True, если коллекция содержит шрифт с указанным именем.
### copyTo(Font[] array, int index) {#copyTo-com.aspose.pdf.Font---int-}
```
public void copyTo(Font[] array, int index)
```


Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [Font\[\]](../../com.aspose.pdf/font) | Массив объектов, которые будут скопированы. |
| index | int | Начальный индекс, с которого будет запущено копирование. |

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
### getHash() {#getHash--}
```
public HashDictionary<String,Font> getHash()
```




**Возвращает:**
[HashDictionary](../../com.aspose.pdf.engine.collections/hashdictionary)
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который можно использовать для синхронизации доступа к коллекции.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### get_Item(int index) {#get-Item-int-}
```
public Font get_Item(int index)
```


Получает элемент шрифта по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель в коллекции. |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public Font get_Item(String name)
```


Получает шрифт из коллекции по имени шрифта. Исключение выдается, если шрифт не найден.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название шрифта. |

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Найден шрифт.
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


Получает значение, указывающее, доступна ли коллекция только для чтения

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public Iterator<Font> iterator()
```


Возвращает перечислитель для всей коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.Font> — объект перечислителя.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


Возвращает перечислитель для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator — объект перечислителя.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Font item) {#remove-com.aspose.pdf.Font-}
```
public boolean remove(Font item)
```


Удаляет указанный элемент из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Font](../../com.aspose.pdf/font) | Объект для удаления |

**Возвращает:**
boolean - true, если элемент был удален из коллекции; в противном случае ложно.
### size() {#size--}
```
public int size()
```


Получает количество элементов объекта Font, фактически содержащихся в коллекции.

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
