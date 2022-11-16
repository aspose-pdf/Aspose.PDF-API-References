---
title: GoToAction
second_title: Aspose.PDF для справки по Java API
description: Представляет действие перехода, которое изменяет представление на указанное местоположение целевой страницы и коэффициент увеличения.
type: docs
weight: 144
url: /ru/java/com.aspose.pdf/gotoaction/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public class GoToAction extends PdfAction
```

Представляет действие перехода, которое изменяет представление на указанное место назначения (страницу, местоположение и коэффициент увеличения).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GoToAction(int page)](#GoToAction-int-) | Конструктор класса GoToAction. |
| [GoToAction(Page page)](#GoToAction-com.aspose.pdf.Page-) | Конструктор класса GoToAction. |
| [GoToAction(Page page, int type, double[] values)](#GoToAction-com.aspose.pdf.Page-int-double...-) | Конструктор класса GoToAction. |
| [GoToAction(ExplicitDestination destination)](#GoToAction-com.aspose.pdf.ExplicitDestination-) | Конструктор. |
| [GoToAction()](#GoToAction--) | Конструктор. |
| [GoToAction(Document doc, String name)](#GoToAction-com.aspose.pdf.Document-java.lang.String-) | Действие, связанное с Named Destination. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestination()](#getDestination--) | Получает пункт назначения для перехода. |
| [getNext()](#getNext--) | Следующие действия по порядку. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Устанавливает пункт назначения для перехода. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GoToAction(int page) {#GoToAction-int-}
```
public GoToAction(int page)
```


Конструктор класса GoToAction.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | целое значение |

### GoToAction(Page page) {#GoToAction-com.aspose.pdf.Page-}
```
public GoToAction(Page page)
```


Конструктор класса GoToAction.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Целевой объект страницы для перехода. |

### GoToAction(Page page, int type, double[] values) {#GoToAction-com.aspose.pdf.Page-int-double...-}
```
public GoToAction(Page page, int type, double[] values)
```


Конструктор класса GoToAction.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница назначения. |
| type | int | Тип назначения. |
| values | double[] | Параметры действия. |

### GoToAction(ExplicitDestination destination) {#GoToAction-com.aspose.pdf.ExplicitDestination-}
```
public GoToAction(ExplicitDestination destination)
```


Конструктор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destination | [ExplicitDestination](../../com.aspose.pdf/explicitdestination) | Явное назначение. |

### GoToAction() {#GoToAction--}
```
public GoToAction()
```


Конструктор.

### GoToAction(Document doc, String name) {#GoToAction-com.aspose.pdf.Document-java.lang.String-}
```
public GoToAction(Document doc, String name)
```


Действие, связанное с Named Destination.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Документ, в котором будет создано действие. |
| name | java.lang.String | Название пункта назначения. |

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
[IAppointment](../../com.aspose.pdf/iappointment) - Значение IAppointment
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
| value | [IAppointment](../../com.aspose.pdf/iappointment) | Значение назначения |

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
