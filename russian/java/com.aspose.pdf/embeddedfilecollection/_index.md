---
title: EmbeddedFileCollection
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий коллекцию встроенных файлов.
type: docs
weight: 97
url: /ru/java/com.aspose.pdf/embeddedfilecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public class EmbeddedFileCollection implements Iterable<FileSpecification>
```

Класс, представляющий коллекцию встроенных файлов.
## Методы

| Метод | Описание |
| --- | --- |
| [add(FileSpecification file)](#add-com.aspose.pdf.FileSpecification-) | Добавляет встроенную спецификацию файла в коллекцию. |
| [add(String key, FileSpecification file)](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Добавляет файл к внедренным файлам с указанным ключом. |
| [clear()](#clear--) | Удалить все встроенные файлы из документа. |
| [contains(FileSpecification item)](#contains-com.aspose.pdf.FileSpecification-) | Определяет, содержит ли коллекция указанный FileSpecification. |
| [copyTo(FileSpecification[] array, int index)](#copyTo-com.aspose.pdf.FileSpecification---int-) | Копирует массив объекта FileSpecification в коллекцию. |
| [delete()](#delete--) | Удалить все встроенные файлы из документа. |
| [delete(String name)](#delete-java.lang.String-) | Удалить встроенный файл по имени. |
| [deleteByKey(String key)](#deleteByKey-java.lang.String-) | Удаляет файл из коллекции по его ключу в коллекции. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findByName(String name)](#findByName-java.lang.String-) | Возвращает внедренный файл по его имени. |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Возвращает список ключей прикрепленных файлов. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает встроенный файл по его индексу. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает внедренный файл по его имени. |
| [hashCode()](#hashCode--) |  |
| [isEmbeddedFilesExist()](#isEmbeddedFilesExist--) | Проверьте, существует ли структура Embedded Files. |
| [isReadOnly()](#isReadOnly--) | Определяет, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к этой коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Возвращает перечислитель коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(FileSpecification item)](#remove-com.aspose.pdf.FileSpecification-) | Удаляет указанный FileSpecification из коллекции. |
| [size()](#size--) | Получает количество встроенных файлов в коллекцию. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(FileSpecification file) {#add-com.aspose.pdf.FileSpecification-}
```
public void add(FileSpecification file)
```


Добавляет встроенную спецификацию файла в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification, который необходимо добавить в коллекцию. |

### add(String key, FileSpecification file) {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
```
public void add(String key, FileSpecification file)
```


Добавляет файл к внедренным файлам с указанным ключом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Введите встроенные файлы. |
| file | [FileSpecification](../../com.aspose.pdf/filespecification) | Спецификация файла. |

### clear() {#clear--}
```
public void clear()
```


Удалить все встроенные файлы из документа.

### contains(FileSpecification item) {#contains-com.aspose.pdf.FileSpecification-}
```
public boolean contains(FileSpecification item)
```


Определяет, содержит ли коллекция указанный FileSpecification. Не поддерживается.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [FileSpecification](../../com.aspose.pdf/filespecification) | Экземпляр FileSpecification |

**Возвращает:**
boolean - логическое значение
### copyTo(FileSpecification[] array, int index) {#copyTo-com.aspose.pdf.FileSpecification---int-}
```
public void copyTo(FileSpecification[] array, int index)
```


Копирует массив объекта FileSpecification в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [FileSpecification\[\]](../../com.aspose.pdf/filespecification) | Массив объектов, которые будут скопированы. |
| index | int | Начальный индекс, с которого будет запущено копирование. |

### delete() {#delete--}
```
public void delete()
```


Удалить все встроенные файлы из документа.

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Удалить встроенный файл по имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя встроенного файла, который необходимо удалить. |

### deleteByKey(String key) {#deleteByKey-java.lang.String-}
```
public void deleteByKey(String key)
```


Удаляет файл из коллекции по его ключу в коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое имя ключа объекта. |

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
### findByName(String name) {#findByName-java.lang.String-}
```
public final FileSpecification findByName(String name)
```


Возвращает внедренный файл по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя файла. |

**Возвращает:**
[FileSpecification](../../com.aspose.pdf/filespecification) Экземпляр FileSpecification Объект спецификации файла, если он найден; в противном случае ноль.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getKeys() {#getKeys--}
```
public final List<String> getKeys()
```


Возвращает список ключей прикрепленных файлов.

**Возвращает:**
java.util.List<java.lang.String> — Список строковых значений
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который можно использовать для синхронизации доступа к этой коллекции.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### get_Item(int index) {#get-Item-int-}
```
public FileSpecification get_Item(int index)
```


Получает встроенный файл по его индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс встроенного файла. Нумерация начинается с 1. |

**Возвращает:**
[FileSpecification](../../com.aspose.pdf/filespecification) - Получена спецификация встроенного файла
### get_Item(String name) {#get-Item-java.lang.String-}
```
public FileSpecification get_Item(String name)
```


Получает внедренный файл по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя встроенного файла. |

**Возвращает:**
[FileSpecification](../../com.aspose.pdf/filespecification) - Получена спецификация встроенного файла.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isEmbeddedFilesExist() {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```


Проверьте, существует ли структура Embedded Files. Возвращает TRUE, если структура существует, и FALSE, если нет. Если документ никогда не содержал встроенных файлов - эта структура не создавалась и отсутствует.

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Определяет, доступна ли коллекция только для чтения. Всегда возвращает ложь.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Получает значение, указывающее, является ли доступ к этой коллекции синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<FileSpecification> iterator()
```


Возвращает перечислитель коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.FileSpecification> — перечислитель коллекции.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.Generic.IGenericEnumerator<FileSpecification> iterator_Rename_Namesake()
```


Возвращает перечислитель коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.FileSpecification> — перечислитель коллекции.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(FileSpecification item) {#remove-com.aspose.pdf.FileSpecification-}
```
public boolean remove(FileSpecification item)
```


Удаляет указанный FileSpecification из коллекции. Не поддерживается.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [FileSpecification](../../com.aspose.pdf/filespecification) | Экземпляр FileSpecification |

**Возвращает:**
boolean - логическое значение
### size() {#size--}
```
public int size()
```


Получает количество встроенных файлов в коллекцию.

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
