---
title: PageLabelCollection
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий коллекцию меток страницы.
type: docs
weight: 263
url: /ru/java/com.aspose.pdf/pagelabelcollection/
---
**Наследование:**
java.lang.Object
```
public class PageLabelCollection
```

Класс, представляющий коллекцию меток страницы.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLabel(int pageIndex)](#getLabel-int-) | Получает метку страницы по индексу страницы (индекс страницы начинается с 0). |
| [getPages()](#getPages--) | Получает индексы страниц в коллекции. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLabel(int pageIndex)](#removeLabel-int-) | Удалить метку по индексу страницы (индекс страницы начинается с 0). |
| [toString()](#toString--) |  |
| [updateLabel(int pageIndex, PageLabel pageLabel)](#updateLabel-int-com.aspose.pdf.PageLabel-) | Обновить метку для заданного индекса страницы (индекс страницы начинается с 0). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getLabel(int pageIndex) {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```


Получает метку страницы по индексу страницы (индекс страницы начинается с 0).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | int | Индекс страницы. |

**Возвращает:**
[PageLabel](../../com.aspose.pdf/pagelabel) - Метка страницы для указанного индекса страницы или null, если метка страницы не существует.
### getPages() {#getPages--}
```
public int[] getPages()
```


Получает индексы страниц в коллекции.

**Возвращает:**
инт[] - Массив целых чисел, содержащий индексы страниц.
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




### removeLabel(int pageIndex) {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```


Удалить метку по индексу страницы (индекс страницы начинается с 0).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | int | Индекс страницы, на которой необходимо удалить метку. |

**Возвращает:**
boolean - true, если операция выполнена успешно.
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### updateLabel(int pageIndex, PageLabel pageLabel) {#updateLabel-int-com.aspose.pdf.PageLabel-}
```
public void updateLabel(int pageIndex, PageLabel pageLabel)
```


Обновить метку для заданного индекса страницы (индекс страницы начинается с 0).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | int | Индекс страницы для изменения метки страницы. |
| pageLabel | [PageLabel](../../com.aspose.pdf/pagelabel) | Новая метка страницы. |

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
