---
title: LaunchAction
second_title: Aspose.PDF для справки по Java API
description: Представляет действие запуска, которое запускает приложение, открывает или печатает документ.
type: docs
weight: 187
url: /ru/java/com.aspose.pdf/launchaction/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class LaunchAction extends PdfAction
```

Представляет действие запуска, которое запускает приложение, открывает или печатает документ.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LaunchAction(String file)](#LaunchAction-java.lang.String-) | Создает действие запуска. |
| [LaunchAction(IDocument document, String file)](#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-) | Создает действие запуска. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFile()](#getFile--) | Получает приложение для запуска или документ для открытия или печати. |
| [getNewWindow()](#getNewWindow--) | Получает флаг, указывающий, следует ли открывать целевой документ в новом окне (влияет только на документы PDF). |
| [getNext()](#getNext--) | Следующие действия по порядку. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFile(String value)](#setFile-java.lang.String-) | Задает запускаемое приложение или открываемый или распечатываемый документ. |
| [setNewWindow(int value)](#setNewWindow-int-) | Устанавливает флаг, указывающий, открывать ли целевой документ в новом окне (влияет только на документы PDF). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LaunchAction(String file) {#LaunchAction-java.lang.String-}
```
public LaunchAction(String file)
```


Создает действие запуска.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Файл, который нужно запустить. |

### LaunchAction(IDocument document, String file) {#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-}
```
public LaunchAction(IDocument document, String file)
```


Создает действие запуска.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ, в котором будет создано действие. |
| file | java.lang.String | Файл, который нужно запустить. |

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
### getFile() {#getFile--}
```
public String getFile()
```


Получает приложение для запуска или документ для открытия или печати.

**Возвращает:**
java.lang.String — строковое значение
### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


Получает флаг, указывающий, следует ли открывать целевой документ в новом окне (влияет только на документы PDF).

**Возвращает:**
int — расширенный логический элемент
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Следующие действия по порядку.

**Возвращает:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - Объект ActionCollection
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




### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


Задает запускаемое приложение или открываемый или распечатываемый документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


Устанавливает флаг, указывающий, открывать ли целевой документ в новом окне (влияет только на документы PDF). расширенное логическое значение

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ExtendedBoolean |

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
