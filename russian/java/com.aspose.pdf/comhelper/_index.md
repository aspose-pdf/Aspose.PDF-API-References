---
title: ComHelper
second_title: Aspose.PDF для справки по Java API
description: Предоставляет методы для COM-клиентов для загрузки документа в Aspose.PDF.
type: docs
weight: 68
url: /ru/java/com.aspose.pdf/comhelper/
---
**Наследование:**
java.lang.Object
```
public class ComHelper
```

Предоставляет методы для COM-клиентов для загрузки документа в Aspose.PDF.

--------------------

Используйте класс ComHelper для загрузки документа из файла или потока в объект Document в приложении COM. Класс Document предоставляет конструктор по умолчанию для создания нового документа, а также предоставляет перегруженные конструкторы для загрузки документа из файла или потока. Если вы используете Aspose.Words из приложения .NET, вы можете напрямую использовать все конструкторы документов, но если вы используете Aspose.PDF из приложения COM, доступен только конструктор документов по умолчанию.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ComHelper()](#ComHelper--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFile(String filename)](#openFile-java.lang.String-) | Просто создайте и верните документ, используя имя файла. |
| [openFile(String filename, LoadOptions options)](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Откройте существующий документ из файла, предоставив необходимые параметры преобразования, чтобы получить документ в формате pdf. |
| [openFile(String filename, String password)](#openFile-java.lang.String-java.lang.String-) | Инициализировать и вернуть новый экземпляр класса Document для работы с зашифрованным документом. |
| [openFile(String filename, String password, boolean isManagedStream)](#openFile-java.lang.String-java.lang.String-boolean-) | Инициализировать новый экземпляр класса Document для работы с зашифрованным документом. |
| [openStream(InputStream input)](#openStream-java.io.InputStream-) | Инициализировать и вернуть новый экземпляр документа из входного потока. |
| [openStream(InputStream input, boolean isManagedStream)](#openStream-java.io.InputStream-boolean-) | Инициализировать и вернуть новый экземпляр документа из входного потока. |
| [openStream(InputStream input, LoadOptions options)](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Откройте и верните существующий документ из потока, обеспечив необходимое преобразование для получения pdf-документа. |
| [openStream(InputStream input, String password)](#openStream-java.io.InputStream-java.lang.String-) | Инициализировать и вернуть новый экземпляр документа из входного потока. |
| [openStream(InputStream input, String password, boolean isManagedStream)](#openStream-java.io.InputStream-java.lang.String-boolean-) | Инициализировать и вернуть новый экземпляр документа из входного потока. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComHelper() {#ComHelper--}
```
public ComHelper()
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




### openFile(String filename) {#openFile-java.lang.String-}
```
public Document openFile(String filename)
```


Просто создайте и верните документ, используя имя файла. То же, что и Document(Stream) .

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Имя файла pdf-документа. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openFile(String filename, LoadOptions options) {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
```
public Document openFile(String filename, LoadOptions options)
```


Откройте существующий документ из файла, предоставив необходимые параметры преобразования, чтобы получить документ в формате pdf.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Входной файл для преобразования в PDF-документ. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Представляет свойства для преобразования имени файла в документ PDF. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openFile(String filename, String password) {#openFile-java.lang.String-java.lang.String-}
```
public Document openFile(String filename, String password)
```


Инициализировать и вернуть новый экземпляр класса Document для работы с зашифрованным документом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Имя файла документа. |
| password | java.lang.String | Пароль пользователя или владельца. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openFile(String filename, String password, boolean isManagedStream) {#openFile-java.lang.String-java.lang.String-boolean-}
```
public Document openFile(String filename, String password, boolean isManagedStream)
```


Инициализировать новый экземпляр класса Document для работы с зашифрованным документом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Имя файла документа. |
| password | java.lang.String | Пароль пользователя или владельца. |
| isManagedStream | boolean | если установлено значение true, внутренний поток закрывается перед выходом; в противном случае нет. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openStream(InputStream input) {#openStream-java.io.InputStream-}
```
public Document openStream(InputStream input)
```


Инициализировать и вернуть новый экземпляр документа из входного потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Поток с документом PDF. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openStream(InputStream input, boolean isManagedStream) {#openStream-java.io.InputStream-boolean-}
```
public Document openStream(InputStream input, boolean isManagedStream)
```


Инициализировать и вернуть новый экземпляр документа из входного потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Поток с документом PDF. |
| isManagedStream | boolean | если установлено значение true, внутренний поток закрывается перед выходом; в противном случае нет. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openStream(InputStream input, LoadOptions options) {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document openStream(InputStream input, LoadOptions options)
```


Откройте и верните существующий документ из потока, обеспечив необходимое преобразование для получения pdf-документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Входной поток для преобразования в документ PDF. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Представляет свойства для преобразования входных данных в документ PDF. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openStream(InputStream input, String password) {#openStream-java.io.InputStream-java.lang.String-}
```
public Document openStream(InputStream input, String password)
```


Инициализировать и вернуть новый экземпляр документа из входного потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Объект входного потока, соответствующий PDF-файл защищен паролем. |
| password | java.lang.String | Пароль пользователя или владельца. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### openStream(InputStream input, String password, boolean isManagedStream) {#openStream-java.io.InputStream-java.lang.String-boolean-}
```
public Document openStream(InputStream input, String password, boolean isManagedStream)
```


Инициализировать и вернуть новый экземпляр документа из входного потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Поток с документом PDF. |
| password | java.lang.String | Пароль пользователя или владельца. |
| isManagedStream | boolean | если установлено значение true, внутренний поток закрывается перед выходом; в противном случае нет. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
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
