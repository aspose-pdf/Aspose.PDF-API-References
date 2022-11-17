---
title: GoToRemoteAction
second_title: Aspose.PDF для справки по Java API
description: Представляет удаленное действие перехода, похожее на обычное действие перехода, но с переходом к месту назначения в другом файле PDF вместо текущего файла.
type: docs
weight: 145
url: /ru/java/com.aspose.pdf/gotoremoteaction/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction), [com.aspose.pdf.GoToAction](../../com.aspose.pdf/gotoaction)
```
public final class GoToRemoteAction extends GoToAction
```

Представляет удаленное действие перехода, похожее на обычное действие перехода, но с переходом к месту назначения в другом файле PDF вместо текущего файла.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GoToRemoteAction(String remotePdf, int remotePageNumber)](#GoToRemoteAction-java.lang.String-int-) | Инициализирует объект GoToRemoteAction. |
| [GoToRemoteAction(String remotePdf, ExplicitDestination destination)](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | Инициализирует объект GoToRemoteAction. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestination()](#getDestination--) | Получает пункт назначения для перехода. |
| [getFile()](#getFile--) | Получает спецификацию файла, в котором находится место назначения. |
| [getNewWindow()](#getNewWindow--) | Получает флаг, указывающий, следует ли открывать целевой документ в новом окне. |
| [getNext()](#getNext--) | Следующие действия по порядку. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Устанавливает пункт назначения для перехода. |
| [setFile(FileSpecification value)](#setFile-com.aspose.pdf.FileSpecification-) | Задает спецификацию файла, в котором находится место назначения. |
| [setNewWindow(int value)](#setNewWindow-int-) | Устанавливает флаг, указывающий, открывать ли целевой документ в новом окне. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GoToRemoteAction(String remotePdf, int remotePageNumber) {#GoToRemoteAction-java.lang.String-int-}
```
public GoToRemoteAction(String remotePdf, int remotePageNumber)
```


Инициализирует объект GoToRemoteAction.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| remotePdf | java.lang.String | Целевой PDF-документ. |
| remotePageNumber | int | Номер целевой страницы. |

### GoToRemoteAction(String remotePdf, ExplicitDestination destination) {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
```
public GoToRemoteAction(String remotePdf, ExplicitDestination destination)
```


Инициализирует объект GoToRemoteAction.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| remotePdf | java.lang.String | Целевой PDF-документ. |
| destination | [ExplicitDestination](../../com.aspose.pdf/explicitdestination) | Место назначения в документе PDF. |

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
### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Получает пункт назначения для перехода.

**Возвращает:**
[IAppointment](../../com.aspose.pdf/iappointment) - место для прыжка
### getFile() {#getFile--}
```
public FileSpecification getFile()
```


Получает спецификацию файла, в котором находится место назначения.

**Возвращает:**
[FileSpecification](../../com.aspose.pdf/filespecification) объект FileSpecification
### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


Получает флаг, указывающий, следует ли открывать целевой документ в новом окне.

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




### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Устанавливает пункт назначения для перехода.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | пункт назначения для прыжка |

### setFile(FileSpecification value) {#setFile-com.aspose.pdf.FileSpecification-}
```
public void setFile(FileSpecification value)
```


Задает спецификацию файла, в котором находится место назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | Значение FileSpecification |

### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


Устанавливает флаг, указывающий, открывать ли целевой документ в новом окне.

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
