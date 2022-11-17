---
title: SubmitFormAction
second_title: Aspose.PDF для справки по Java API
description: Класс, описывающий действие отправки формы.
type: docs
weight: 342
url: /ru/java/com.aspose.pdf/submitformaction/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class SubmitFormAction extends PdfAction
```

Класс, описывающий действие отправки формы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SubmitFormAction()](#SubmitFormAction--) | Инициализирует объект SubmitFormAction. |
## Поля

| Поле | Описание |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL-FORMAT) | Если установлено, любые отправленные значения полей, представляющие даты, должны быть преобразованы в стандартный формат. |
| [EMBED_FORM](#EMBED-FORM) | Если установлено, запись F представленного FDF должна быть спецификацией файла, содержащей встроенный файловый поток, представляющий файл PDF, из которого отправляется FDF. |
| [EXCLUDE](#EXCLUDE) | Если флажок не установлен, массив Fields указывает, какие поля следует включить в отправку. |
| [EXCL_F_KEY](#EXCL-F-KEY) | Если установлено, представленный FDF должен исключить запись F. |
| [EXCL_NON_USER_ANNOTS](#EXCL-NON-USER-ANNOTS) | Если он установлен, он должен включать только те аннотации разметки, запись T которых соответствует имени текущего пользователя. |
| [EXPORT_FORMAT](#EXPORT-FORMAT) | Если установлено, имена полей и значения должны быть представлены в формате формы HTML. |
| [GET_METHOD](#GET-METHOD) | Если установлено, имена полей и значения должны быть отправлены с использованием HTTP-запроса GET. |
| [INCLUDE_ANNOTATIONS](#INCLUDE-ANNOTATIONS) | Если установлено, отправленный файл FDF должен включать в себя все аннотации разметки в базовом документе PDF. |
| [INCLUDE_APPEND_SAVES](#INCLUDE-APPEND-SAVES) | Если установлено, представленный файл FDF должен включать содержимое всех добавочных обновлений. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE-NO-VALUE-FIELDS) | Если установлено, должны быть отправлены все поля, обозначенные массивом Fields и флагом Include/Exclude. |
| [SUBMIT_COORDINATES](#SUBMIT-COORDINATES) | Если установлено, координаты щелчка мыши, вызвавшего действие отправки формы, должны передаваться как часть данных формы. |
| [SUBMIT_PDF](#SUBMIT-PDF) | Если установлено, документ должен быть представлен в формате PDF с использованием типа содержимого MIME application/pdf. |
| [XFDF](#XFDF) | Если установлено, имена полей и значения должны быть представлены в формате XFDF. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFlags()](#getFlags--) | Получает флаги действия отправки |
| [getNext()](#getNext--) | Следующие действия по порядку. |
| [getUrl()](#getUrl--) | Целевой URL. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFlags(int value)](#setFlags-int-) | Устанавливает флаги действия отправки |
| [setUrl(FileSpecification value)](#setUrl-com.aspose.pdf.FileSpecification-) | Целевой URL. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubmitFormAction() {#SubmitFormAction--}
```
public SubmitFormAction()
```


Инициализирует объект SubmitFormAction.

### CANONICAL_FORMAT {#CANONICAL-FORMAT}
```
public static final int CANONICAL_FORMAT
```


Если установлено, любые отправленные значения полей, представляющие даты, должны быть преобразованы в стандартный формат.

### EMBED_FORM {#EMBED-FORM}
```
public static final int EMBED_FORM
```


Если установлено, запись F представленного FDF должна быть спецификацией файла, содержащей встроенный файловый поток, представляющий файл PDF, из которого отправляется FDF.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```


Если флажок не установлен, массив Fields указывает, какие поля следует включить в отправку.

### EXCL_F_KEY {#EXCL-F-KEY}
```
public static final int EXCL_F_KEY
```


Если установлено, представленный FDF должен исключить запись F.

### EXCL_NON_USER_ANNOTS {#EXCL-NON-USER-ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```


Если он установлен, он должен включать только те аннотации разметки, запись T которых соответствует имени текущего пользователя.

### EXPORT_FORMAT {#EXPORT-FORMAT}
```
public static final int EXPORT_FORMAT
```


Если установлено, имена полей и значения должны быть представлены в формате формы HTML.

### GET_METHOD {#GET-METHOD}
```
public static final int GET_METHOD
```


Если установлено, имена полей и значения должны быть отправлены с использованием HTTP-запроса GET.

### INCLUDE_ANNOTATIONS {#INCLUDE-ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```


Если установлено, отправленный файл FDF должен включать в себя все аннотации разметки в базовом документе PDF.

### INCLUDE_APPEND_SAVES {#INCLUDE-APPEND-SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```


Если установлено, представленный файл FDF должен включать содержимое всех добавочных обновлений.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE-NO-VALUE-FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```


Если установлено, должны быть отправлены все поля, обозначенные массивом Fields и флагом Include/Exclude.

### SUBMIT_COORDINATES {#SUBMIT-COORDINATES}
```
public static final int SUBMIT_COORDINATES
```


Если установлено, координаты щелчка мыши, вызвавшего действие отправки формы, должны передаваться как часть данных формы.

### SUBMIT_PDF {#SUBMIT-PDF}
```
public static final int SUBMIT_PDF
```


Если установлено, документ должен быть представлен в формате PDF с использованием типа содержимого MIME application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```


Если установлено, имена полей и значения должны быть представлены в формате XFDF.

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
### getFlags() {#getFlags--}
```
public int getFlags()
```


Получает флаги действия отправки

**Возвращает:**
интервал - целочисленное значение
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Следующие действия по порядку.

**Возвращает:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - Объект ActionCollection
### getUrl() {#getUrl--}
```
public FileSpecification getUrl()
```


Целевой URL.

**Возвращает:**
[FileSpecification](../../com.aspose.pdf/filespecification) - Значение спецификации файла
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




### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Устанавливает флаги действия отправки

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setUrl(FileSpecification value) {#setUrl-com.aspose.pdf.FileSpecification-}
```
public void setUrl(FileSpecification value)
```


Целевой URL.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | Значение FileSpecification |

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
