---
title: IncorrectFontUsageException
second_title: Aspose.PDF для справки по Java API
description: Исключение, возникающее при неправильном использовании шрифта.
type: docs
weight: 17
url: /ru/java/com.aspose.pdf.exceptions/incorrectfontusageexception/
---
**Наследование:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException, [com.aspose.pdf.exceptions.PdfException](../../com.aspose.pdf.exceptions/pdfexception), [com.aspose.pdf.exceptions.InvalidFileFormatException](../../com.aspose.pdf.exceptions/invalidfileformatexception)
```
public final class IncorrectFontUsageException extends InvalidFileFormatException
```

Исключение, возникающее при неправильном использовании шрифта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [IncorrectFontUsageException(String message)](#IncorrectFontUsageException-java.lang.String-) | Инициализирует новый экземпляр класса IncorrectFontUsageException. |
| [IncorrectFontUsageException(String message, System.Exception innerException)](#IncorrectFontUsageException-java.lang.String-com.aspose.ms.System.Exception-) | Инициализирует новый экземпляр класса IncorrectFontUsageException с указанным сообщением об ошибке и ссылкой на внутреннее исключение, которое является причиной этого исключения. |
## Методы

| Метод | Описание |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressed()](#getSuppressed--) |  |
| [getType()](#getType--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IncorrectFontUsageException(String message) {#IncorrectFontUsageException-java.lang.String-}
```
public IncorrectFontUsageException(String message)
```


Инициализирует новый экземпляр класса IncorrectFontUsageException.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Сообщение. |

### IncorrectFontUsageException(String message, System.Exception innerException) {#IncorrectFontUsageException-java.lang.String-com.aspose.ms.System.Exception-}
```
public IncorrectFontUsageException(String message, System.Exception innerException)
```


Инициализирует новый экземпляр класса IncorrectFontUsageException с указанным сообщением об ошибке и ссылкой на внутреннее исключение, которое является причиной этого исключения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Сообщение об ошибке, объясняющее причину исключения. |
| innerException | com.aspose.ms.System.Exception | Исключение, являющееся причиной текущего исключения, или пустая ссылка (Nothing в Visual Basic), если внутреннее исключение не указано. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Возвращает:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Возвращает:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getInnerException() {#getInnerException--}
```
public Throwable getInnerException()
```




**Возвращает:**
java.lang.Throwable
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Возвращает:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```




**Возвращает:**
java.lang.String
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Возвращает:**
java.lang.StackTraceElement[]
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Возвращает:**
java.lang.Throwable[]
### getType() {#getType--}
```
public System.Type getType()
```




**Возвращает:**
com.aspose.ms.System.Type
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Возвращает:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

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
