---
title: XfdfReader
second_title: Aspose.PDF для справки по Java API
description: Класс, выполняющий чтение формата XFDF.
type: docs
weight: 413
url: /ru/java/com.aspose.pdf/xfdfreader/
---
**Наследование:**
java.lang.Object
```
public final class XfdfReader
```

Класс, выполняющий чтение формата XFDF.

--------------------

`Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf");`
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XfdfReader()](#XfdfReader--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements(System.Xml.XmlReader reader)](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Разбирает файл XFDF и возвращает информацию в виде хеш-таблицы. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readAnnotations(InputStream stream, IDocument document)](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Импортируйте аннотации из файла XFDF и поместите их в документ. |
| [readFields(InputStream stream, IDocument document)](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Импортировать значения полей из файла XFDF. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XfdfReader() {#XfdfReader--}
```
public XfdfReader()
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
### getElements(System.Xml.XmlReader reader) {#getElements-com.aspose.ms.System.Xml.XmlReader-}
```
public static Map getElements(System.Xml.XmlReader reader)
```


Разбирает файл XFDF и возвращает информацию в виде хеш-таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | com.aspose.ms.System.Xml.XmlReader | XmlReader для исходного файла. |

**Возвращает:**
java.util.Map — хеш-таблица с информацией, полученной из файла XFDF.
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




### readAnnotations(InputStream stream, IDocument document) {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
```
public static void readAnnotations(InputStream stream, IDocument document)
```


Импортируйте аннотации из файла XFDF и поместите их в документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток, содержащий файл XFDF. |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ, в который будут добавлены аннотации. |

### readFields(InputStream stream, IDocument document) {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
```
public static void readFields(InputStream stream, IDocument document)
```


Импортировать значения полей из файла XFDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий данные XFDF. |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ, в который будут импортированы данные полей. |

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
