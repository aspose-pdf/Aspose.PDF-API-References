---
title: PdfOutOfMemoryException
second_title: Aspose.PDF для справки по Java API
description: Представляет ошибки OutOfMemory, возникающие во время выполнения приложения PDF.
type: docs
weight: 28
url: /ru/java/com.aspose.pdf.exceptions/pdfoutofmemoryexception/
---
**Наследование:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class PdfOutOfMemoryException extends System.OutOfMemoryException
```

Представляет ошибки OutOfMemory, возникающие во время выполнения приложения PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfOutOfMemoryException(String message)](#PdfOutOfMemoryException-java.lang.String-) | Инициализирует новый экземпляр класса OutOfMemoryException. |
| [PdfOutOfMemoryException(String message, Throwable innerException)](#PdfOutOfMemoryException-java.lang.String-java.lang.Throwable-) | Инициализирует новый экземпляр класса PdfException с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной этого исключения. |
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
### PdfOutOfMemoryException(String message) {#PdfOutOfMemoryException-java.lang.String-}
```
public PdfOutOfMemoryException(String message)
```


Инициализирует новый экземпляр класса OutOfMemoryException.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Сообщение. |

### PdfOutOfMemoryException(String message, Throwable innerException) {#PdfOutOfMemoryException-java.lang.String-java.lang.Throwable-}
```
public PdfOutOfMemoryException(String message, Throwable innerException)
```


Инициализирует новый экземпляр класса PdfException с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной этого исключения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Сообщение об ошибке, объясняющее причину исключения. |
| innerException | java.lang.Throwable | Исключение, являющееся причиной текущего исключения, или пустая ссылка |

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
