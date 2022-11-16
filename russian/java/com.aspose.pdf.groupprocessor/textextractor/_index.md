---
title: TextExtractor
second_title: Aspose.PDF для справки по Java API
description: Представляет экземпляр для взаимодействия с экстрактором.
type: docs
weight: 12
url: /ru/java/com.aspose.pdf.groupprocessor/textextractor/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.groupprocessor.IVentureLicenseTarget

**Все реализованные интерфейсы:**
[com.aspose.pdf.groupprocessor.interfaces.IPdfTypeExtractor](../../com.aspose.pdf.groupprocessor.interfaces/ipdftypeextractor)
```
public final class TextExtractor extends IVentureLicenseTarget implements IPdfTypeExtractor
```

Представляет экземпляр для взаимодействия с экстрактором.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextExtractor()](#TextExtractor--) | Создает экземпляр TextExtractor. |
## Поля

| Поле | Описание |
| --- | --- |
| [_numberedPages](#-numberedPages) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [buildProperties(ByteRange range, PdfTreeNode parentNode)](#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-) | Строит дерево узлов, содержащих все параметры pdf с их значениями. |
| [buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue)](#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-boolean-) | Строит дерево узлов, содержащих все параметры pdf с их значениями. |
| [close()](#close--) | Закрывает все ресурсы, используемые этим экземпляром. |
| [dispose()](#dispose--) | Dispose object Этот метод устарел, вместо него используйте close(). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAllText()](#extractAllText--) | Извлекает текст из документа |
| [extractAllTextInternal()](#extractAllTextInternal--) |  |
| [extractPageText(int pageNumber)](#extractPageText-int-) | Извлекает текст со страницы |
| [getClass()](#getClass--) |  |
| [getPageCount()](#getPageCount--) | Получает количество страниц в документе. |
| [getVentureLicense()](#getVentureLicense--) |  |
| [getVersion()](#getVersion--) | Только для внутреннего использования |
| [hashCode()](#hashCode--) |  |
| [initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization)](#initialize-com.aspose.ms.System.IO.Stream-int-boolean-) | Инициализирует экземпляр TextExtractor. |
| [initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization)](#initialize-com.aspose.ms.System.IO.Stream-java.lang.String-int-boolean-) | Инициализирует экземпляр TextExtractor. |
| [initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization)](#initialize-java.lang.String-int-boolean-) | Инициализирует экземпляр TextExtractor. |
| [initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization)](#initialize-java.lang.String-java.lang.String-int-boolean-) | Инициализирует экземпляр TextExtractor. |
| [initializeAlternative(System.IO.Stream pdfDocumentStream)](#initializeAlternative-com.aspose.ms.System.IO.Stream-) | Инициализирует экземпляр TextExtractor. |
| [initializeAlternative(System.IO.Stream pdfDocumentStream, String password)](#initializeAlternative-com.aspose.ms.System.IO.Stream-java.lang.String-) | Инициализирует экземпляр TextExtractor. |
| [initializeAlternative(String pdfDocumentPath)](#initializeAlternative-java.lang.String-) | Инициализирует экземпляр TextExtractor. |
| [initializeAlternative(String pdfDocumentPath, String password)](#initializeAlternative-java.lang.String-java.lang.String-) | Инициализирует экземпляр TextExtractor. |
| [isFastExtractionUsed()](#isFastExtractionUsed--) | Возвращает TRUE, если использовалось быстрое извлечение |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setVentureLicense(VentureLicense license)](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextExtractor() {#TextExtractor--}
```
public TextExtractor()
```


Создает экземпляр TextExtractor.

### _numberedPages {#-numberedPages}
```
public final System.Collections.Generic.Dictionary<Integer,Page> _numberedPages
```


### buildProperties(ByteRange range, PdfTreeNode parentNode) {#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-}
```
public long buildProperties(ByteRange range, PdfTreeNode parentNode)
```


Строит дерево узлов, содержащих все параметры pdf с их значениями.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| range | com.aspose.pdf.groupprocessor.ByteRange | Диапазон байтов, где анализировать параметры. |
| parentNode | com.aspose.pdf.groupprocessor.PdfTreeNode | Начальный (корневой) узел для построения дерева. |

**Возвращает:**
long - длинное значение, последний индекс анализируемого диапазона.
### buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue) {#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-boolean-}
```
public long buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue)
```


Строит дерево узлов, содержащих все параметры pdf с их значениями.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| range | com.aspose.pdf.groupprocessor.ByteRange | Диапазон байтов, где анализировать параметры. |
| parentNode | com.aspose.pdf.groupprocessor.PdfTreeNode | Начальный (корневой) узел для построения дерева. |
| extractJustValue | boolean | Для рекурсивного вызова. Просто показывает, что следующая рекурсивная функция должна найти значение параметра, но не сам параметр. |

**Возвращает:**
long — последний индекс анализируемого диапазона.
### close() {#close--}
```
public void close()
```


Закрывает все ресурсы, используемые этим экземпляром.

### dispose() {#dispose--}
```
public void dispose()
```


Dispose object Этот метод устарел, вместо него используйте close().

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
### extractAllText() {#extractAllText--}
```
public String[] extractAllText()
```


Извлекает текст из документа

**Возвращает:**
java.lang.String[] — массив строк, представляющих текст документа
### extractAllTextInternal() {#extractAllTextInternal--}
```
public String[] extractAllTextInternal()
```




**Возвращает:**
java.lang.String[]
### extractPageText(int pageNumber) {#extractPageText-int-}
```
public String extractPageText(int pageNumber)
```


Извлекает текст со страницы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | 1 номер страницы |

**Возвращает:**
java.lang.String — Текст
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получает количество страниц в документе.

**Возвращает:**
int - количество страниц
### getVentureLicense() {#getVentureLicense--}
```
public final VentureLicense getVentureLicense()
```




**Возвращает:**
[VentureLicense](../../com.aspose.pdf.engine.licensemanagement/venturelicense)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Только для внутреннего использования

**Возвращает:**
java.lang.String — строковый объект
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization) {#initialize-com.aspose.ms.System.IO.Stream-int-boolean-}
```
public void initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Поток, содержащий PDF-документ. |
| bufferSize | int | Максимальный размер содержимого в байтах, которое может храниться в памяти. |
| allowAsyncInitialization | boolean | Разрешает асинхронную инициализацию ресурсов. |

### initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization) {#initialize-com.aspose.ms.System.IO.Stream-java.lang.String-int-boolean-}
```
public void initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Поток, содержащий PDF-документ. |
| password | java.lang.String | Пароль документа. |
| bufferSize | int | Максимальный размер содержимого в байтах, которое может храниться в памяти. |
| allowAsyncInitialization | boolean | Разрешает асинхронную инициализацию ресурсов. |

### initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization) {#initialize-java.lang.String-int-boolean-}
```
public void initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Путь к pdf-документу. |
| bufferSize | int | Максимальный размер содержимого в байтах, которое может храниться в памяти. |
| allowAsyncInitialization | boolean | Разрешает асинхронную инициализацию ресурсов. |

### initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization) {#initialize-java.lang.String-java.lang.String-int-boolean-}
```
public void initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Путь к pdf-документу. |
| password | java.lang.String | Пароль документа. |
| bufferSize | int | Максимальный размер содержимого в байтах, которое может храниться в памяти. |
| allowAsyncInitialization | boolean | Разрешает асинхронную инициализацию ресурсов. |

### initializeAlternative(System.IO.Stream pdfDocumentStream) {#initializeAlternative-com.aspose.ms.System.IO.Stream-}
```
public void initializeAlternative(System.IO.Stream pdfDocumentStream)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Поток, содержащий PDF-документ. |

### initializeAlternative(System.IO.Stream pdfDocumentStream, String password) {#initializeAlternative-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public void initializeAlternative(System.IO.Stream pdfDocumentStream, String password)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | Поток, содержащий PDF-документ. |
| password | java.lang.String |  |

### initializeAlternative(String pdfDocumentPath) {#initializeAlternative-java.lang.String-}
```
public void initializeAlternative(String pdfDocumentPath)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Путь к pdf-документу. |

### initializeAlternative(String pdfDocumentPath, String password) {#initializeAlternative-java.lang.String-java.lang.String-}
```
public void initializeAlternative(String pdfDocumentPath, String password)
```


Инициализирует экземпляр TextExtractor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | Путь к pdf-документу. |
| password | java.lang.String |  |

### isFastExtractionUsed() {#isFastExtractionUsed--}
```
public boolean isFastExtractionUsed()
```


Возвращает TRUE, если использовалось быстрое извлечение

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




### setVentureLicense(VentureLicense license) {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
```
public final void setVentureLicense(VentureLicense license)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| license | [VentureLicense](../../com.aspose.pdf.engine.licensemanagement/venturelicense) |  |

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
