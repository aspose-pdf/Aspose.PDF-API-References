---
title: HideAction
second_title: Aspose.PDF для справки по Java API
description: Представляет действие скрытия, которое скрывает или показывает одну или несколько аннотаций на экране, устанавливая или снимая их флажки «Скрытые».
type: docs
weight: 152
url: /ru/java/com.aspose.pdf/hideaction/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public class HideAction extends PdfAction
```

Представляет действие скрытия, которое скрывает или показывает одну или несколько аннотаций на экране, устанавливая или снимая их флажки «Скрытые».
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HideAction(Annotation annotation)](#HideAction-com.aspose.pdf.Annotation-) | Инициализирует новый экземпляр класса HideAction для указанной аннотации. |
| [HideAction(Annotation annotation, boolean isHidden)](#HideAction-com.aspose.pdf.Annotation-boolean-) | Инициализирует новый экземпляр класса HideAction для указанной аннотации и флага невидимости. |
| [HideAction(String fieldName)](#HideAction-java.lang.String-) | Инициализирует новый экземпляр класса HideAction для указанного имени поля. |
| [HideAction(String fieldName, boolean isHidden)](#HideAction-java.lang.String-boolean-) | Инициализирует новый экземпляр класса HideAction для указанного имени поля и флага невидимости. |
| [HideAction(Annotation[] annotations)](#HideAction-com.aspose.pdf.Annotation---) | Инициализирует новый экземпляр класса HideAction для указанных аннотаций. |
| [HideAction(Annotation[] annotations, boolean isHidden)](#HideAction-com.aspose.pdf.Annotation---boolean-) | Инициализирует новый экземпляр класса HideAction для указанных аннотаций и флага невидимости. |
| [HideAction(String[] names)](#HideAction-java.lang.String---) | Инициализирует новый экземпляр класса HideAction для указанных имен полей. |
| [HideAction(String[] names, boolean isHidden)](#HideAction-java.lang.String---boolean-) | Инициализирует новый экземпляр класса HideAction для указанных имен полей и флага невидимости. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNext()](#getNext--) | Следующие действия по порядку. |
| [hashCode()](#hashCode--) |  |
| [isHidden()](#isHidden--) | Получает или задает статус аннотаций для скрытия/отображения. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHidden(boolean value)](#setHidden-boolean-) | Получает или задает статус аннотаций для скрытия/отображения. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HideAction(Annotation annotation) {#HideAction-com.aspose.pdf.Annotation-}
```
public HideAction(Annotation annotation)
```


Инициализирует новый экземпляр класса HideAction для указанной аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация, которую нужно скрыть. |

### HideAction(Annotation annotation, boolean isHidden) {#HideAction-com.aspose.pdf.Annotation-boolean-}
```
public HideAction(Annotation annotation, boolean isHidden)
```


Инициализирует новый экземпляр класса HideAction для указанной аннотации и флага невидимости.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация, которую нужно скрыть или показать. |
| isHidden | boolean | Флаг, указывающий, следует ли скрыть аннотацию (true) или показать ее (false). |

### HideAction(String fieldName) {#HideAction-java.lang.String-}
```
public HideAction(String fieldName)
```


Инициализирует новый экземпляр класса HideAction для указанного имени поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Текстовая строка, задающая полное имя поля интерактивной формы. |

### HideAction(String fieldName, boolean isHidden) {#HideAction-java.lang.String-boolean-}
```
public HideAction(String fieldName, boolean isHidden)
```


Инициализирует новый экземпляр класса HideAction для указанного имени поля и флага невидимости.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Текстовая строка, задающая полное имя поля интерактивной формы. |
| isHidden | boolean | Флаг, указывающий, следует ли скрыть поле (true) или показать его (false). |

### HideAction(Annotation[] annotations) {#HideAction-com.aspose.pdf.Annotation---}
```
public HideAction(Annotation[] annotations)
```


Инициализирует новый экземпляр класса HideAction для указанных аннотаций.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotations | [Annotation\[\]](../../com.aspose.pdf/annotation) | Массив аннотаций, которые нужно скрыть. |

### HideAction(Annotation[] annotations, boolean isHidden) {#HideAction-com.aspose.pdf.Annotation---boolean-}
```
public HideAction(Annotation[] annotations, boolean isHidden)
```


Инициализирует новый экземпляр класса HideAction для указанных аннотаций и флага невидимости.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotations | [Annotation\[\]](../../com.aspose.pdf/annotation) | Массив аннотаций, которые нужно скрыть или показать. |
| isHidden | boolean | Флаг, указывающий, следует ли скрыть аннотации (true) или показать их (false). |

### HideAction(String[] names) {#HideAction-java.lang.String---}
```
public HideAction(String[] names)
```


Инициализирует новый экземпляр класса HideAction для указанных имен полей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| names | java.lang.String[] | Массив строк, задающий полные имена полей интерактивной формы. |

### HideAction(String[] names, boolean isHidden) {#HideAction-java.lang.String---boolean-}
```
public HideAction(String[] names, boolean isHidden)
```


Инициализирует новый экземпляр класса HideAction для указанных имен полей и флага невидимости.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| names | java.lang.String[] | Массив строк, задающий полные имена полей интерактивной формы. |
| isHidden | boolean | Флаг, указывающий, следует ли скрыть поля (true) или показать их (false). |

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
### isHidden() {#isHidden--}
```
public boolean isHidden()
```


Получает или задает статус аннотаций для скрытия/отображения.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setHidden(boolean value) {#setHidden-boolean-}
```
public void setHidden(boolean value)
```


Получает или задает статус аннотаций для скрытия/отображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
