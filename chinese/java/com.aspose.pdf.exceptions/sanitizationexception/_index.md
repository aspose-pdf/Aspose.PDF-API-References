---
title: SanitizationException
second_title: 用于 Java API 参考的 Aspose.PDF
description: 清理操作失败时抛出的异常。
type: docs
weight: 29
url: /zh/java/com.aspose.pdf.exceptions/sanitizationexception/
---
**遗产：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public final class SanitizationException extends System.Exception
```

清理操作失败时抛出的异常。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SanitizationException()](#SanitizationException--) | 初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)班级。 |
| [SanitizationException(String message)](#SanitizationException-java.lang.String-) | 初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)班级。 |
| [SanitizationException(String message, RuntimeException innerException)](#SanitizationException-java.lang.String-java.lang.RuntimeException-) | 初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)带有指定错误消息和对导致此异常的内部异常的引用的类。 |
| [SanitizationException(RuntimeException innerException)](#SanitizationException-java.lang.RuntimeException-) | 初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)带有指定错误消息和对导致此异常的内部异常的引用的类。 |
## 方法

| 方法 | 描述 |
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
### SanitizationException() {#SanitizationException--}
```
public SanitizationException()
```


初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)班级。

### SanitizationException(String message) {#SanitizationException-java.lang.String-}
```
public SanitizationException(String message)
```


初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)班级。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 消息。 |

### SanitizationException(String message, RuntimeException innerException) {#SanitizationException-java.lang.String-java.lang.RuntimeException-}
```
public SanitizationException(String message, RuntimeException innerException)
```


初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)带有指定错误消息和对导致此异常的内部异常的引用的类。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 解释异常原因的错误消息。 |
| innerException | java.lang.RuntimeException | 导致当前异常的异常，如果未指定内部异常，则为空引用（在 Visual Basic 中为 Nothing）。 |

### SanitizationException(RuntimeException innerException) {#SanitizationException-java.lang.RuntimeException-}
```
public SanitizationException(RuntimeException innerException)
```


初始化一个新的实例[SanitizationException](../../com.aspose.pdf.exceptions/sanitizationexception)带有指定错误消息和对导致此异常的内部异常的引用的类。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| innerException | java.lang.RuntimeException | 导致当前异常的异常，如果未指定内部异常，则为空引用（在 Visual Basic 中为 Nothing）。 |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**退货：**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**退货：**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getInnerException() {#getInnerException--}
```
public Throwable getInnerException()
```




**退货：**
java.lang.Throwable
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**退货：**
java.lang.字符串
### getMessage() {#getMessage--}
```
public String getMessage()
```




**退货：**
java.lang.字符串
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**退货：**
java.lang.StackTraceElement[]
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**退货：**
java.lang.Throwable[]
### getType() {#getType--}
```
public System.Type getType()
```




**退货：**
com.aspose.ms.System.类型
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**退货：**
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




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
