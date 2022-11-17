---
title: Id
second_title: Aspose.PDF для справки по Java API
description: Представляет структуру идентификатора файла.
type: docs
weight: 165
url: /ru/java/com.aspose.pdf/id/
---
**Наследование:**
java.lang.Object
```
public class Id
```

Представляет структуру идентификатора файла.

--------------------

```
Document doc = new Document("example.pdf");
 String original = doc.getId().getOriginal();
 String modified = doc.getId().getModified();
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getModified()](#getModified--) | Изменение идентификатора на основе содержимого документа на момент последнего обновления. |
| [getOriginal()](#getOriginal--) | Постоянный идентификатор, основанный на содержимом документа на момент его первоначального создания. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
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
### getModified() {#getModified--}
```
public String getModified()
```


Изменение идентификатора на основе содержимого документа на момент последнего обновления.

**Возвращает:**
java.lang.String — строковое значение
### getOriginal() {#getOriginal--}
```
public String getOriginal()
```


Постоянный идентификатор, основанный на содержимом документа на момент его первоначального создания.

**Возвращает:**
java.lang.String — строковое значение
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
