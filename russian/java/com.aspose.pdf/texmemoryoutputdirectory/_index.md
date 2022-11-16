---
title: TeXMemoryOutputDirectory
second_title: Aspose.PDF для справки по Java API
description: Реализует выборку выходного потока из памяти.
type: docs
weight: 358
url: /ru/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.tex.ITeXOutputDirectory
```
public class TeXMemoryOutputDirectory implements ITeXOutputDirectory
```

Реализует выборку выходного потока из памяти. Вы можете использовать его, например, когда вы не хотите, чтобы сопровождающий вывод (например, файл журнала) записывался на диск, но вы хотели бы прочитать его впоследствии из памяти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TeXMemoryOutputDirectory()](#TeXMemoryOutputDirectory--) | Создает новый экземпляр. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Удаляет экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFile(String fileName, String[] fullName)](#getFile-java.lang.String-java.lang.String---) | Возвращает поток для чтения. |
| [getFile(String fileName, String[] fullName, boolean searchSubdirectories)](#getFile-java.lang.String-java.lang.String---boolean-) | Возвращает поток для чтения. |
| [getOutputFile(String fileName, String[] fullName)](#getOutputFile-java.lang.String-java.lang.String---) | Возвращает поток для записи. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TeXMemoryOutputDirectory() {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```


Создает новый экземпляр.

### close() {#close--}
```
public void close()
```


Удаляет экземпляр.

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
### getFile(String fileName, String[] fullName) {#getFile-java.lang.String-java.lang.String---}
```
public final InputStream getFile(String fileName, String[] fullName)
```


Возвращает поток для чтения.

Без поиска файла в подкаталогах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| fullName | java.lang.String[] | Полное имя файла. В этой реализации не имеет никакого эффекта. |

**Возвращает:**
java.io.InputStream — поток.
### getFile(String fileName, String[] fullName, boolean searchSubdirectories) {#getFile-java.lang.String-java.lang.String---boolean-}
```
public InputStream getFile(String fileName, String[] fullName, boolean searchSubdirectories)
```


Возвращает поток для чтения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| fullName | java.lang.String[] | Полное имя файла. |
| searchSubdirectories | boolean | Указывает, искать ли файл в подкаталогах. В этой реализации не имеет никакого эффекта. |

**Возвращает:**
java.io.InputStream — поток.
### getOutputFile(String fileName, String[] fullName) {#getOutputFile-java.lang.String-java.lang.String---}
```
public OutputStream getOutputFile(String fileName, String[] fullName)
```


Возвращает поток для записи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Строковое значение Имя файла. |
| fullName | java.lang.String[] | Строковое значение в массиве Полное имя файла. |

**Возвращает:**
java.io.OutputStream — экземпляр OutputStream
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
