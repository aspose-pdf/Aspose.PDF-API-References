---
title: DocumentDevice
second_title: Aspose.PDF для справки по Java API
description: Абстрактный класс для всех устройств, который используется для обработки всего pdf-документа.
type: docs
weight: 14
url: /ru/java/com.aspose.pdf.devices/documentdevice/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device)
```
public abstract class DocumentDevice extends Device
```

Абстрактный класс для всех устройств, который используется для обработки всего pdf-документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DocumentDevice()](#DocumentDevice--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Выполните бинаризацию Брэдли для входного потока. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(IDocument document, int fromPage, int toPage, OutputStream output)](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Каждое устройство представляет некоторую операцию над документом, например, мы можем преобразовать документ pdf в другой формат. |
| [process(IDocument document, int fromPage, int toPage, String outputFileName)](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Обрабатывает определенные страницы документа и сохраняет результаты в файл. |
| [process(IDocument document, OutputStream output)](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [process(IDocument document, String outputFileName)](#process-com.aspose.pdf.IDocument-java.lang.String-) | Обрабатывает весь документ и сохраняет результаты в файл. |
| [processInternal(IDocument document, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Каждое устройство представляет некоторую операцию над документом, например, мы можем преобразовать документ pdf в другой формат. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentDevice() {#DocumentDevice--}
```
public DocumentDevice()
```


### binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold) {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
```
public void binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)
```


Выполните бинаризацию Брэдли для входного потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImageStream | java.io.InputStream | Входной поток изображений. |
| outputImageStream | java.io.OutputStream | Выходной поток изображения. |
| threshold | double | Пороговое значение от 0,0 до 1,0. |

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




### process(IDocument document, int fromPage, int toPage, OutputStream output) {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
```
public void process(IDocument document, int fromPage, int toPage, OutputStream output)
```


Каждое устройство представляет некоторую операцию над документом, например, мы можем преобразовать документ pdf в другой формат.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| fromPage | int | Определяет страницу, с которой следует начать обработку. |
| toPage | int | Определяет последнюю страницу для обработки. |
| output | java.io.OutputStream | Определяет поток, в котором хранятся результаты обработки. |

### process(IDocument document, int fromPage, int toPage, String outputFileName) {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
```
public void process(IDocument document, int fromPage, int toPage, String outputFileName)
```


Обрабатывает определенные страницы документа и сохраняет результаты в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| fromPage | int | Первая страница для начала обработки. |
| toPage | int | Последняя страница обработки. |
| outputFileName | java.lang.String | Определяет файл, в котором хранятся результаты обработки. |

### process(IDocument document, OutputStream output) {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public void process(IDocument document, OutputStream output)
```


Обрабатывает весь документ и сохраняет результаты в поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| output | java.io.OutputStream | Определяет поток, в котором хранятся результаты обработки. |

### process(IDocument document, String outputFileName) {#process-com.aspose.pdf.IDocument-java.lang.String-}
```
public void process(IDocument document, String outputFileName)
```


Обрабатывает весь документ и сохраняет результаты в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| outputFileName | java.lang.String | Определяет файл, в котором хранятся результаты обработки. |

### processInternal(IDocument document, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, System.IO.Stream output)
```


Обрабатывает весь документ и сохраняет результаты в поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| output | com.aspose.ms.System.IO.Stream | Определяет поток, в котором хранятся результаты обработки. |

### processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
```
public abstract void processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)
```


Каждое устройство представляет некоторую операцию над документом, например, мы можем преобразовать документ pdf в другой формат.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| fromPage | int | Определяет страницу, с которой следует начать обработку. |
| toPage | int | Определяет последнюю страницу для обработки. |
| output | com.aspose.ms.System.IO.Stream | Определяет поток, в котором хранятся результаты обработки. |

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
