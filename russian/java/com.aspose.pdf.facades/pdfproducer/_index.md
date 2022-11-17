---
title: PdfProducer
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для создания PDF из других форматов.
type: docs
weight: 51
url: /ru/java/com.aspose.pdf.facades/pdfproducer/
---
**Наследование:**
java.lang.Object
```
public abstract class PdfProducer
```

Представляет класс для создания PDF из других форматов.

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 try
 {
     PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile);
     // Успешно создан файл PDF.
 }
 catch (Exception e)
 {
     // Сделай что-нибудь...
 }
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImportOptions(int format)](#getImportOptions-int-) | Получите ImportOptions для указанного формата импорта. |
| [getProducer(ImportOptions options)](#getProducer-com.aspose.pdf.ImportOptions-) | Получить производителя для указанного параметра импорта. |
| [getProducer(int format)](#getProducer-int-) | Получить производителя для указанного формата импорта. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [produce(InputStream inputStream, ImportOptions options, OutputStream outputStream)](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | Создайте файл PDF, используя указанный параметр импорта. |
| [produce(InputStream inputStream, ImportOptions options, String outputFileName)](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce(InputStream inputStream, int format, OutputStream outputStream)](#produce-java.io.InputStream-int-java.io.OutputStream-) | Создайте поток PDF, используя указанный формат импорта. |
| [produce(InputStream inputStream, int format, String outputFileName)](#produce-java.io.InputStream-int-java.lang.String-) | Создайте файл PDF, используя указанный формат импорта. |
| [produce(String inputFileName, ImportOptions options, OutputStream outputStream)](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce(String inputFileName, ImportOptions options, String outputFileName)](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | Создайте файл PDF, используя указанный параметр импорта. |
| [produce(String inputFileName, int format, OutputStream outputStream)](#produce-java.lang.String-int-java.io.OutputStream-) |  |
| [produce(String inputFileName, int format, String outputFileName)](#produce-java.lang.String-int-java.lang.String-) | Создайте файл PDF, используя указанный формат импорта. |
| [produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream)](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getImportOptions(int format) {#getImportOptions-int-}
```
public static ImportOptions getImportOptions(int format)
```


Получите ImportOptions для указанного формата импорта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | Формат импорта. |

**Возвращает:**
[ImportOptions](../../com.aspose.pdf/importoptions) - Возможность импорта.
### getProducer(ImportOptions options) {#getProducer-com.aspose.pdf.ImportOptions-}
```
public static PdfProducer getProducer(ImportOptions options)
```


Получить производителя для указанного параметра импорта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | Вариант импорта |

**Возвращает:**
[PdfProducer](../../com.aspose.pdf.facades/pdfproducer) - производитель PDF.
### getProducer(int format) {#getProducer-int-}
```
public static PdfProducer getProducer(int format)
```


Получить производителя для указанного формата импорта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | Вариант импорта |

**Возвращает:**
[PdfProducer](../../com.aspose.pdf.facades/pdfproducer) - производитель PDF.
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




### produce(InputStream inputStream, ImportOptions options, OutputStream outputStream) {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
```
public static void produce(InputStream inputStream, ImportOptions options, OutputStream outputStream)
```


Создайте файл PDF, используя указанный параметр импорта.

--------------------

```
This sample shows how to produce Pdf stream from CGM stream.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileInputStream inputStream = File.OpenRead(inputFile))
 using (FileOutputStream outputStream = File.Create(outputFile))
 {
     PdfProducer.produce(inputStream, importOptions, outputStream);
 }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | Вариант импорта. |
| outputStream | java.io.OutputStream | Выходной PDF-поток. |

### produce(InputStream inputStream, ImportOptions options, String outputFileName) {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}
```
public static void produce(InputStream inputStream, ImportOptions options, String outputFileName)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputFileName | java.lang.String |  |

### produce(InputStream inputStream, int format, OutputStream outputStream) {#produce-java.io.InputStream-int-java.io.OutputStream-}
```
public static void produce(InputStream inputStream, int format, OutputStream outputStream)
```


Создайте поток PDF, используя указанный формат импорта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| format | int | Формат импорта. |
| outputStream | java.io.OutputStream | Выходной PDF-поток. |

### produce(InputStream inputStream, int format, String outputFileName) {#produce-java.io.InputStream-int-java.lang.String-}
```
public static void produce(InputStream inputStream, int format, String outputFileName)
```


Создайте файл PDF, используя указанный формат импорта.

--------------------

```
This sample shows how to produce Pdf file from CGM stream.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 using (FileInputStream inputStream = File.OpenRead(inputFile))
 using (FileOutputStream outputStream = File.Create(outputFile))
 {
     PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream);
 }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| format | int | Формат импорта. |
| outputFileName | java.lang.String | Выходной PDF-файл |

### produce(String inputFileName, ImportOptions options, OutputStream outputStream) {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
```
public static void produce(String inputFileName, ImportOptions options, OutputStream outputStream)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | java.lang.String |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputStream | java.io.OutputStream |  |

### produce(String inputFileName, ImportOptions options, String outputFileName) {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
```
public static void produce(String inputFileName, ImportOptions options, String outputFileName)
```


Создайте файл PDF, используя указанный параметр импорта.

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 PdfProducer.produce(inputStream, importOptions, outputStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | java.lang.String | Введите имя файла. |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | Вариант импорта. |
| outputFileName | java.lang.String | Выходной PDF-поток. |

### produce(String inputFileName, int format, OutputStream outputStream) {#produce-java.lang.String-int-java.io.OutputStream-}
```
public static void produce(String inputFileName, int format, OutputStream outputStream)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | java.lang.String |  |
| format | int |  |
| outputStream | java.io.OutputStream |  |

### produce(String inputFileName, int format, String outputFileName) {#produce-java.lang.String-int-java.lang.String-}
```
public static void produce(String inputFileName, int format, String outputFileName)
```


Создайте файл PDF, используя указанный формат импорта.

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | java.lang.String | Введите имя файла. |
| format | int | Формат импорта. |
| outputFileName | java.lang.String | Выходной PDF-файл |

### produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream) {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
```
public static void produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | com.aspose.ms.System.IO.Stream |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |

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
