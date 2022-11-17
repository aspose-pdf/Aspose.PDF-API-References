---
title: DocumentFactory
second_title: Aspose.PDF для справки по Java API
description: Класс, который позволяет создавать/загружать документы разных типов.
type: docs
weight: 93
url: /ru/java/com.aspose.pdf/documentfactory/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.IVentureLicenseTarget
```
public class DocumentFactory extends IVentureLicenseTarget
```

Класс, который позволяет создавать/загружать документы разных типов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DocumentFactory()](#DocumentFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createDocument()](#createDocument--) | Создать пустой документ. |
| [createDocument(InputStream input)](#createDocument-java.io.InputStream-) | Загрузить документ из потока. |
| [createDocument(InputStream input, LoadOptions options)](#createDocument-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Создать документ. |
| [createDocument(InputStream input, String password)](#createDocument-java.io.InputStream-java.lang.String-) | Загрузить защищенный паролем документ из потока. |
| [createDocument(String fileName)](#createDocument-java.lang.String-) | Загрузить документ из файла. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentFactory() {#DocumentFactory--}
```
public DocumentFactory()
```


### createDocument() {#createDocument--}
```
public Document createDocument()
```


Создать пустой документ.

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Создан документ.
### createDocument(InputStream input) {#createDocument-java.io.InputStream-}
```
public Document createDocument(InputStream input)
```


Загрузить документ из потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Входной поток. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Создан документ.
### createDocument(InputStream input, LoadOptions options) {#createDocument-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document createDocument(InputStream input, LoadOptions options)
```


Создать документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Входной поток. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Варианты загрузки документов. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Объект документа
### createDocument(InputStream input, String password) {#createDocument-java.io.InputStream-java.lang.String-}
```
public Document createDocument(InputStream input, String password)
```


Загрузить защищенный паролем документ из потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | java.io.InputStream | Исходный поток. |
| password | java.lang.String | Пароль для доступа к документу. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Создан документ.
### createDocument(String fileName) {#createDocument-java.lang.String-}
```
public Document createDocument(String fileName)
```


Загрузить документ из файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла PDF. |

**Возвращает:**
[Document](../../com.aspose.pdf/document) - Создан документ.
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
