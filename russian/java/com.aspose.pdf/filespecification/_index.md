---
title: FileSpecification
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий встроенный файл.
type: docs
weight: 118
url: /ru/java/com.aspose.pdf/filespecification/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class FileSpecification implements System.IDisposable, Closeable
```

Класс, представляющий встроенный файл.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileSpecification(IPdfPrimitive specification)](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Спецификация файла |
| [FileSpecification(String file)](#FileSpecification-java.lang.String-) | Конструктор для FileSpecification |
| [FileSpecification(System.IO.Stream stream, String name)](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Конструктор для спецификации файла. |
| [FileSpecification(InputStream stream, String name)](#FileSpecification-java.io.InputStream-java.lang.String-) | Конструктор для спецификации файла. |
| [FileSpecification(String file, String description)](#FileSpecification-java.lang.String-java.lang.String-) | Конструктор для FileSpecification. |
| [FileSpecification(System.IO.Stream stream, String name, String description)](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Конструктор для FileSpecification. |
| [FileSpecification(InputStream stream, String name, String description)](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Конструктор для FileSpecification. |
| [FileSpecification(String fileName, Annotation annot)](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Конструктор для FileSpecification. |
| [FileSpecification()](#FileSpecification--) | Создайте новую пустую спецификацию файла. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Утилизируйте содержимое. |
| [dispose()](#dispose--) | Утилизируйте содержимое. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFRelationship()](#getAFRelationship--) | Связанный файл Отношение. |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | Получает файл содержимого. |
| [getContentsInternal()](#getContentsInternal--) | Получает файл содержимого. |
| [getDescription()](#getDescription--) | Получает текст, связанный со спецификацией файла. |
| [getEncoding()](#getEncoding--) | Получает формат кодировки. |
| [getEncryptedPayload()](#getEncryptedPayload--) | Получает зашифрованную полезную нагрузку. |
| [getEngineDict()](#getEngineDict--) | Словарь Pdf, содержащий информацию о файле. |
| [getEngineObj()](#getEngineObj--) | Только внутренний |
| [getFileSystem()](#getFileSystem--) | Получает имя файловой системы. |
| [getMIMEType()](#getMIMEType--) | Получает подтип встроенного файла |
| [getName()](#getName--) | Получает имя спецификации файла. |
| [getParams()](#getParams--) | Получает параметры файла. |
| [getStreamContents()](#getStreamContents--) | Получает содержимое файла в виде потока. |
| [getUnicodeName()](#getUnicodeName--) | Получает юникодное имя спецификации файла. |
| [getValue(String key)](#getValue-java.lang.String-) | Получает параметр приложения. |
| [hashCode()](#hashCode--) |  |
| [isIncludeContents()](#isIncludeContents--) | Если true, содержимое файла будет включено в спецификацию файла. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAFRelationship(AFRelationship value)](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Связанный файл Отношение. |
| [setContents(byte[] value)](#setContents-byte---) | Устанавливает файл содержимого. |
| [setContents(InputStream value)](#setContents-java.io.InputStream-) | Устанавливает файл содержимого. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Задает текст, связанный со спецификацией файла. |
| [setEncoding(int value)](#setEncoding-int-) | Устанавливает формат кодирования. |
| [setFileSystem(String value)](#setFileSystem-java.lang.String-) | Устанавливает имя файловой системы. |
| [setIncludeContents(boolean value)](#setIncludeContents-boolean-) | Если true, содержимое файла будет включено в спецификацию файла. |
| [setMIMEType(String value)](#setMIMEType-java.lang.String-) | Устанавливает тип MIME. |
| [setName(String value)](#setName-java.lang.String-) | Задает имя спецификации файла. |
| [setParams(FileParams value)](#setParams-com.aspose.pdf.FileParams-) | Устанавливает параметры файла. |
| [setUnicodeName(String value)](#setUnicodeName-java.lang.String-) | Устанавливает юникодное имя спецификации файла. |
| [setValue(String key, String value)](#setValue-java.lang.String-java.lang.String-) | Устанавливает специфический для приложения параметр. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSpecification(IPdfPrimitive specification) {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public FileSpecification(IPdfPrimitive specification)
```


Спецификация файла

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| specification | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Объект IPdfPrimitive |

### FileSpecification(String file) {#FileSpecification-java.lang.String-}
```
public FileSpecification(String file)
```


Конструктор для FileSpecification

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Путь к файлу. |

### FileSpecification(System.IO.Stream stream, String name) {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public FileSpecification(System.IO.Stream stream, String name)
```


Конструктор для спецификации файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, содержащий файл данных. |
| name | java.lang.String | Спецификация файла. |

### FileSpecification(InputStream stream, String name) {#FileSpecification-java.io.InputStream-java.lang.String-}
```
public FileSpecification(InputStream stream, String name)
```


Конструктор для спецификации файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий файл данных. |
| name | java.lang.String | Спецификация файла. |

### FileSpecification(String file, String description) {#FileSpecification-java.lang.String-java.lang.String-}
```
public FileSpecification(String file, String description)
```


Конструктор для FileSpecification.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Путь к файлу. |
| description | java.lang.String | Описание файла. |

### FileSpecification(System.IO.Stream stream, String name, String description) {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
```
public FileSpecification(System.IO.Stream stream, String name, String description)
```


Конструктор для FileSpecification.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, который будет использоваться в документе. |
| name | java.lang.String | Строка спецификации файла. |
| description | java.lang.String | Описание файла. |

### FileSpecification(InputStream stream, String name, String description) {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
```
public FileSpecification(InputStream stream, String name, String description)
```


Конструктор для FileSpecification.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, который будет использоваться в документе. |
| name | java.lang.String | Строка спецификации файла. |
| description | java.lang.String | Описание файла. |

### FileSpecification(String fileName, Annotation annot) {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
```
public FileSpecification(String fileName, Annotation annot)
```


Конструктор для FileSpecification.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Строковый объект |
| annot | [Annotation](../../com.aspose.pdf/annotation) | Объект аннотации |

### FileSpecification() {#FileSpecification--}
```
public FileSpecification()
```


Создайте новую пустую спецификацию файла.

### close() {#close--}
```
public void close()
```


Утилизируйте содержимое.

### dispose() {#dispose--}
```
public void dispose()
```


Утилизируйте содержимое.

Этот метод устарел, вместо него используйте close().

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
### getAFRelationship() {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```


Связанный файл Отношение.

**Возвращает:**
[AFRelationship](../../com.aspose.pdf/afrelationship) - Элемент AFRelationship
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContents() {#getContents--}
```
public InputStream getContents()
```


Получает файл содержимого.

**Возвращает:**
java.io.InputStream — объект InputStream
### getContentsInternal() {#getContentsInternal--}
```
public System.IO.Stream getContentsInternal()
```


Получает файл содержимого.

**Возвращает:**
com.aspose.ms.System.IO.Stream — объект потока
### getDescription() {#getDescription--}
```
public String getDescription()
```


Получает текст, связанный со спецификацией файла.

**Возвращает:**
java.lang.String — строковое значение
### getEncoding() {#getEncoding--}
```
public int getEncoding()
```


Получает формат кодировки. Возможные значения: Zip — файл сжат ZIP, None — файл не сжат.

**Возвращает:**
интервал - целочисленное значение
### getEncryptedPayload() {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```


Получает зашифрованную полезную нагрузку.

**Возвращает:**
[EncryptedPayload](../../com.aspose.pdf/encryptedpayload) - Экземпляр EncryptedPayload
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


Словарь Pdf, содержащий информацию о файле. Только внутренний

**Возвращает:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - Объект IPdfDictionary
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


Только внутренний

**Возвращает:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - Объект IPdfObject
### getFileSystem() {#getFileSystem--}
```
public String getFileSystem()
```


Получает имя файловой системы.

**Возвращает:**
java.lang.String — строковое значение
### getMIMEType() {#getMIMEType--}
```
public String getMIMEType()
```


Получает подтип встроенного файла

**Возвращает:**
java.lang.String — строковое значение
### getName() {#getName--}
```
public String getName()
```


Получает имя спецификации файла.

**Возвращает:**
java.lang.String — строковое значение
### getParams() {#getParams--}
```
public FileParams getParams()
```


Получает параметры файла.

**Возвращает:**
[FileParams](../../com.aspose.pdf/fileparams) - Объект FileParams
### getStreamContents() {#getStreamContents--}
```
public InputStream getStreamContents()
```


Получает содержимое файла в виде потока. Содержимое не загружается в память, что позволяет уменьшить использование памяти. Но этот поток не поддерживает позиционирование и свойство Length. Если вам нужны эти функции, используйте свойство Contents.

**Возвращает:**
java.io.InputStream — объект InputStream
### getUnicodeName() {#getUnicodeName--}
```
public String getUnicodeName()
```


Получает юникодное имя спецификации файла.

**Возвращает:**
java.lang.String — строковое значение
### getValue(String key) {#getValue-java.lang.String-}
```
public final String getValue(String key)
```


Получает параметр приложения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Имя параметра. |

**Возвращает:**
java.lang.String — Строковое значение — если параметр найден; в противном случае ноль.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isIncludeContents() {#isIncludeContents--}
```
public boolean isIncludeContents()
```


Если true, содержимое файла будет включено в спецификацию файла.

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




### setAFRelationship(AFRelationship value) {#setAFRelationship-com.aspose.pdf.AFRelationship-}
```
public final void setAFRelationship(AFRelationship value)
```


Связанный файл Отношение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AFRelationship](../../com.aspose.pdf/afrelationship) | Элемент AFRelationship |

### setContents(byte[] value) {#setContents-byte---}
```
public void setContents(byte[] value)
```


Устанавливает файл содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] | массив байтов |

### setContents(InputStream value) {#setContents-java.io.InputStream-}
```
public void setContents(InputStream value)
```


Устанавливает файл содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Задает текст, связанный со спецификацией файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setEncoding(int value) {#setEncoding-int-}
```
public void setEncoding(int value)
```


Устанавливает формат кодирования. Возможные значения: Zip — файл сжат ZIP, None — файл не сжат.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setFileSystem(String value) {#setFileSystem-java.lang.String-}
```
public void setFileSystem(String value)
```


Устанавливает имя файловой системы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setIncludeContents(boolean value) {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```


Если true, содержимое файла будет включено в спецификацию файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMIMEType(String value) {#setMIMEType-java.lang.String-}
```
public void setMIMEType(String value)
```


Устанавливает тип MIME.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Задает имя спецификации файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setParams(FileParams value) {#setParams-com.aspose.pdf.FileParams-}
```
public void setParams(FileParams value)
```


Устанавливает параметры файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileParams](../../com.aspose.pdf/fileparams) | Объект FileParams |

### setUnicodeName(String value) {#setUnicodeName-java.lang.String-}
```
public void setUnicodeName(String value)
```


Устанавливает юникодное имя спецификации файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setValue(String key, String value) {#setValue-java.lang.String-java.lang.String-}
```
public final void setValue(String key, String value)
```


Устанавливает специфический для приложения параметр.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Имя параметра. |
| value | java.lang.String | Новое значение параметра. |

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
