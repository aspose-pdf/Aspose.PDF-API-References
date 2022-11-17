---
title: WarningCallback
second_title: Aspose.PDF для справки по Java API
description: Интерфейс для поддержки механизма обратного вызова пользователей.
type: docs
weight: 398
url: /ru/java/com.aspose.pdf/warningcallback/
---
**Наследование:**
java.lang.Object
```
public abstract class WarningCallback
```

Интерфейс для поддержки механизма обратного вызова пользователя.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WarningCallback()](#WarningCallback--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warning(WarningInfo warning)](#warning-com.aspose.pdf.WarningInfo-) | Метод обратного вызова для некоторых программных уведомлений. |
### WarningCallback() {#WarningCallback--}
```
public WarningCallback()
```


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

### warning(WarningInfo warning) {#warning-com.aspose.pdf.WarningInfo-}
```
public abstract WarningCallback.ReturnAction warning(WarningInfo warning)
```


Метод обратного вызова для некоторых программных уведомлений.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| warning | [WarningInfo](../../com.aspose.pdf/warninginfo) | предупредительная информация для некоторого произошедшего предупреждения |

**Возвращает:**
[ReturnAction](../../com.aspose.pdf/returnaction) - результат дальнейшей работы программы