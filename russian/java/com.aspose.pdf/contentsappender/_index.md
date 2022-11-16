---
title: ContentsAppender
second_title: Aspose.PDF для справки по Java API
description: Выполняет изменения содержимого только в режиме APPEND.
type: docs
weight: 73
url: /ru/java/com.aspose.pdf/contentsappender/
---
**Наследование:**
java.lang.Object
```
public class ContentsAppender
```

Выполняет изменения содержимого только в режиме APPEND. этот режим позволяет избежать ненужного и тяжелого разбора содержимого до того, как в него будут внесены какие-либо изменения. Он только добавляет новые операторы в конец или в начало содержимого
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ContentsAppender(Page page)](#ContentsAppender-com.aspose.pdf.Page-) | Инициализировать новый экземпляр приложения содержимого с прикрепленной страницей |
| [ContentsAppender(XForm form)](#ContentsAppender-com.aspose.pdf.XForm-) | Инициализирует новый экземпляр приложения contets с помощью Form XObject. |
## Методы

| Метод | Описание |
| --- | --- |
| [appendToBegin(System.Collections.Generic.List<Operator> operators)](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | Добавляет операторы в конец содержимого |
| [appendToBegin(Operator op)](#appendToBegin-com.aspose.pdf.Operator-) | Добавляет оператор в конец содержимого |
| [appendToBegin(Operator[] operators)](#appendToBegin-com.aspose.pdf.Operator---) | Добавляет операторы в конец содержимого |
| [appendToEnd(System.Collections.Generic.List<Operator> operators)](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | Добавляет операторы в начало содержимого |
| [appendToEnd(Operator op)](#appendToEnd-com.aspose.pdf.Operator-) | Добавляет оператор в начало содержимого |
| [appendToEnd(Operator[] operators)](#appendToEnd-com.aspose.pdf.Operator---) | Добавляет операторы в начало содержимого |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginCode()](#getBeginCode--) | Строка, содержащая операторы для вставки в начало страницы. |
| [getBeginOperators()](#getBeginOperators--) | операторы начала возврата |
| [getClass()](#getClass--) |  |
| [getEndCode()](#getEndCode--) | Stirng, содержащий операторы для добавления в конец страницы. |
| [getEndOperators()](#getEndOperators--) | возвращает конечные операторы |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resumeUpdate()](#resumeUpdate--) | возобновляет обновление документа |
| [setBeginCode(String value)](#setBeginCode-java.lang.String-) | Строка, содержащая операторы для вставки в начало страницы. |
| [setEndCode(String value)](#setEndCode-java.lang.String-) | Строка, содержащая операторы для вставки в начало страницы. |
| [suppressUpdate()](#suppressUpdate--) | Подавляет обновление данных содержимого Содержимое не обновляется до тех пор, пока не будет вызвано ResumeUpdate |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | это новая версия UpdateData, которая позволяет избежать декодирования существующего содержимого. |
| [updateDataOld()](#updateDataOld--) | Необходимо вызвать, чтобы применить изменения |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentsAppender(Page page) {#ContentsAppender-com.aspose.pdf.Page-}
```
public ContentsAppender(Page page)
```


Инициализировать новый экземпляр приложения содержимого с прикрепленной страницей

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |

### ContentsAppender(XForm form) {#ContentsAppender-com.aspose.pdf.XForm-}
```
public ContentsAppender(XForm form)
```


Инициализирует новый экземпляр приложения contets с помощью Form XObject.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | объект XForm |

### appendToBegin(System.Collections.Generic.List<Operator> operators) {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public void appendToBegin(System.Collections.Generic.List<Operator> operators)
```


Добавляет операторы в конец содержимого

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> |  Список объектов |

### appendToBegin(Operator op) {#appendToBegin-com.aspose.pdf.Operator-}
```
public void appendToBegin(Operator op)
```


Добавляет оператор в конец содержимого

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Объект оператора |

### appendToBegin(Operator[] operators) {#appendToBegin-com.aspose.pdf.Operator---}
```
public void appendToBegin(Operator[] operators)
```


Добавляет операторы в конец содержимого

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | Массив операторов |

### appendToEnd(System.Collections.Generic.List<Operator> operators) {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public void appendToEnd(System.Collections.Generic.List<Operator> operators)
```


Добавляет операторы в начало содержимого

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> |  Список объектов |

### appendToEnd(Operator op) {#appendToEnd-com.aspose.pdf.Operator-}
```
public void appendToEnd(Operator op)
```


Добавляет оператор в начало содержимого

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Объект оператора |

### appendToEnd(Operator[] operators) {#appendToEnd-com.aspose.pdf.Operator---}
```
public void appendToEnd(Operator[] operators)
```


Добавляет операторы в начало содержимого

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | Массив операторов |

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
### getBeginCode() {#getBeginCode--}
```
public String getBeginCode()
```


Строка, содержащая операторы для вставки в начало страницы.

**Возвращает:**
java.lang.String — строковый объект
### getBeginOperators() {#getBeginOperators--}
```
public System.Collections.Generic.List<Operator> getBeginOperators()
```


операторы начала возврата

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> — объект списка
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEndCode() {#getEndCode--}
```
public String getEndCode()
```


Stirng, содержащий операторы для добавления в конец страницы.

**Возвращает:**
java.lang.String — строковый объект
### getEndOperators() {#getEndOperators--}
```
public System.Collections.Generic.List<Operator> getEndOperators()
```


возвращает конечные операторы

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> — объект списка
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




### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


возобновляет обновление документа

### setBeginCode(String value) {#setBeginCode-java.lang.String-}
```
public void setBeginCode(String value)
```


Строка, содержащая операторы для вставки в начало страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setEndCode(String value) {#setEndCode-java.lang.String-}
```
public void setEndCode(String value)
```


Строка, содержащая операторы для вставки в начало страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Подавляет обновление данных содержимого Содержимое не обновляется до тех пор, пока не будет вызвано ResumeUpdate

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### updateData() {#updateData--}
```
public void updateData()
```


это новая версия UpdateData, которая позволяет избежать декодирования существующего содержимого.

### updateDataOld() {#updateDataOld--}
```
public void updateDataOld()
```


Необходимо вызвать, чтобы применить изменения

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
