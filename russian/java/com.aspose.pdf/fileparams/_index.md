---
title: FileParams
second_title: Aspose.PDF для справки по Java API
description: Определяет встроенный словарь параметров файла, который должен содержать дополнительную информацию о файле.
type: docs
weight: 116
url: /ru/java/com.aspose.pdf/fileparams/
---
**Наследование:**
java.lang.Object
```
public final class FileParams
```

Определяет встроенный словарь параметров файла, который должен содержать дополнительную информацию о файле.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileParams(FileSpecification spec)](#FileParams-com.aspose.pdf.FileSpecification-) | Конструктор класса FileParams. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckSum()](#getCheckSum--) | 16-байтовая строка, представляющая собой контрольную сумму байтов несжатого встроенного файла. |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | Получите дату и время создания встроенного файла. |
| [getModDate()](#getModDate--) | Получите дату и время последнего изменения внедренного файла. |
| [getSize()](#getSize--) | Размер несжатого встроенного файла в байтах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Установите дату и время создания встроенного файла. |
| [setModDate(Date value)](#setModDate-java.util.Date-) | Установите дату и время последнего изменения внедренного файла. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileParams(FileSpecification spec) {#FileParams-com.aspose.pdf.FileSpecification-}
```
public FileParams(FileSpecification spec)
```


Конструктор класса FileParams.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| spec | [FileSpecification](../../com.aspose.pdf/filespecification) | Спецификация файла. |

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
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


16-байтовая строка, представляющая собой контрольную сумму байтов несжатого встроенного файла. Контрольная сумма вычисляется путем применения стандартного алгоритма дайджеста сообщения MD5 к байтам встроенного файлового потока.

**Возвращает:**
java.lang.String — строковое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Получите дату и время создания встроенного файла.

**Возвращает:**
[Date](../../java.util/date) - Объект даты
### getModDate() {#getModDate--}
```
public Date getModDate()
```


Получите дату и время последнего изменения внедренного файла.

**Возвращает:**
[Date](../../java.util/date) - Объект даты
### getSize() {#getSize--}
```
public int getSize()
```


Размер несжатого встроенного файла в байтах.

**Возвращает:**
интервал - целочисленное значение
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




### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Установите дату и время создания встроенного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Объект даты |

### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


Установите дату и время последнего изменения внедренного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Объект даты |

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
