---
title: HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF для справки по Java API
description: Если свойство SplitToPages у HtmlSaveOptions, то при преобразовании PDF в HTML создается несколько HTML-файлов, по одному HTML-файлу на конвертируемую страницу.
type: docs
weight: 20
url: /ru/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Наследование:**
java.lang.Object
```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo
```

Если свойство SplitToPages у HtmlSaveOptions, то при преобразовании PDF в HTML создается несколько HTML-файлов (один HTML-файл на конвертируемую страницу). Этот класс представляет собой набор данных, связанных с произвольным сохранением разметки одной HTML-страницы при преобразовании PDF в HTML.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | Устанавливается конвертером. |
| [getHtmlHostPageNumber()](#getHtmlHostPageNumber--) | Устанавливается конвертером. |
| [getPdfHostPageNumber()](#getPdfHostPageNumber--) | Устанавливается конвертером. |
| [getSupposedFileName()](#getSupposedFileName--) | Устанавливается конвертером. |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | При необходимости должен быть установлен в пользовательском коде. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContentStream(InputStream contentStream)](#setContentStream-java.io.InputStream-) | Устанавливается конвертером. |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | При необходимости должен быть установлен в пользовательском коде. |
| [setHtmlHostPageNumber(int htmlHostPageNumber)](#setHtmlHostPageNumber-int-) | Устанавливается конвертером. |
| [setPdfHostPageNumber(int pdfHostPageNumber)](#setPdfHostPageNumber-int-) | Устанавливается конвертером. |
| [setSupposedFileName(String supposedFileName)](#setSupposedFileName-java.lang.String-) | Устанавливается конвертером. |
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
### getContentStream() {#getContentStream--}
```
public InputStream getContentStream()
```


Устанавливается конвертером. Представляет сохраненный HTML как поток

**Возвращает:**
java.io.InputStream — экземпляр InputStream
### getHtmlHostPageNumber() {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```


Устанавливается конвертером. Если установлено свойство SplitToPages, то при конвертации создается несколько HTML-файлов (один HTML-файл на конвертируемую страницу). Это свойство содержит порядковый номер сохраненного файла HTML-страницы. Свойство можно использовать в логике пользовательского кода, чтобы решить, как обрабатывать или где сохранять HTML-страницу, и если разделение на страницах отключено, это значение всегда содержит «1», поскольку в этом случае для всего исходного документа создается только одна большая HTML-страница. .

**Возвращает:**
интервал - целочисленное значение
### getPdfHostPageNumber() {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```


Устанавливается конвертером. Если задано свойство SplitToPages, то при конвертации создается несколько HTML-файлов (один HTML-файл на конвертируемую страницу). Это свойство сообщает пользовательскому коду, из какой страницы исходного PDF-файла была создана сохраненная HTML-разметка. Если исходный номер страницы по какой-то причине неизвестен или SplitOnPages=false, то это свойство всегда содержит '0', что сигнализирует о том, что конвертер не может предоставить точный исходный номер страницы PDF для предоставленного файла HTML-разметки.

**Возвращает:**
интервал - целочисленное значение
### getSupposedFileName() {#getSupposedFileName--}
```
public String getSupposedFileName()
```


Устанавливается конвертером. Предполагаемое имя файла, которое переходит от преобразователя к коду пользовательского метода. Может использоваться в пользовательском коде, чтобы решить, как обрабатывать или где сохранять содержимое.

**Возвращает:**
java.lang.String — строковое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCustomProcessingCancelled() {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```


При необходимости должен быть установлен в пользовательском коде. Этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предоставленную html-разметку необходимо обрабатывать не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. Таким образом, установка этого флага в пользовательском коде означает, что пользовательский код не обрабатывал указанный файл, и конвертер должен обрабатывать его сам.

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




### setContentStream(InputStream contentStream) {#setContentStream-java.io.InputStream-}
```
public void setContentStream(InputStream contentStream)
```


Устанавливается конвертером. Представляет сохраненный HTML как поток

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentStream | java.io.InputStream | Экземпляр InputStream |

### setCustomProcessingCancelled(boolean customProcessingCancelled) {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```


При необходимости должен быть установлен в пользовательском коде. Этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предоставленную html-разметку необходимо обрабатывать не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. Таким образом, установка этого флага в пользовательском коде означает, что пользовательский код не обрабатывал указанный файл, и конвертер должен обрабатывать его сам.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customProcessingCancelled | boolean | логическое значение |

### setHtmlHostPageNumber(int htmlHostPageNumber) {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```


Устанавливается конвертером. Если установлено свойство SplitToPages, то при конвертации создается несколько HTML-файлов (один HTML-файл на конвертируемую страницу). Это свойство содержит порядковый номер сохраненного файла HTML-страницы. Свойство можно использовать в логике пользовательского кода, чтобы решить, как обрабатывать или где сохранять HTML-страницу, и если разделение на страницах отключено, это значение всегда содержит «1», поскольку в этом случае для всего исходного документа создается только одна большая HTML-страница. .

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlHostPageNumber | int | целое значение |

### setPdfHostPageNumber(int pdfHostPageNumber) {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```


Устанавливается конвертером. Если задано свойство SplitToPages, то при конвертации создается несколько HTML-файлов (один HTML-файл на конвертируемую страницу). Это свойство сообщает пользовательскому коду, из какой страницы исходного PDF-файла была создана сохраненная HTML-разметка. Если исходный номер страницы по какой-то причине неизвестен или SplitOnPages=false, то это свойство всегда содержит '0', что сигнализирует о том, что конвертер не может предоставить точный исходный номер страницы PDF для предоставленного файла HTML-разметки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfHostPageNumber | int | целое значение |

### setSupposedFileName(String supposedFileName) {#setSupposedFileName-java.lang.String-}
```
public void setSupposedFileName(String supposedFileName)
```


Устанавливается конвертером. Предполагаемое имя файла, которое переходит от преобразователя к коду пользовательского метода. Может использоваться в пользовательском коде, чтобы решить, как обрабатывать или где сохранять содержимое.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| supposedFileName | java.lang.String | Строковое значение |

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
