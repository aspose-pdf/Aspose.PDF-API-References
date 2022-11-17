---
title: UnifiedSaveOptions.ConversionProgressEventHandler
second_title: Aspose.PDF для справки по Java API
description: Представляет класс с абстрактным методом, который обычно предоставляется вызывающей стороной, и обрабатывает события выполнения, поступающие от преобразователя.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf/unifiedsaveoptions.conversionprogresseventhandler/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class UnifiedSaveOptions.ConversionProgressEventHandler extends System.MulticastDelegate
```

Представляет класс с абстрактным методом, который обычно предоставляется вызывающей стороной, и обрабатывает события выполнения, поступающие от преобразователя. Обычно такой предоставленный обработчик клиента может использоваться для отображения общего прогресса преобразования на консоли или в строке выполнения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ConversionProgressEventHandler()](#ConversionProgressEventHandler--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [beginInvoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | внутренний метод |
| [combine(System.Delegate arg0, System.Delegate arg1)](#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [combine(System.Delegate[] arg0)](#combine-com.aspose.ms.System.Delegate...-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | внутренний метод |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getInvocationList()](#getInvocationList--) |  |
| [hashCode()](#hashCode--) |  |
| [invoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo)](#invoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-) | Представляет класс с абстрактным методом, который обычно предоставляется вызывающей стороной, и обрабатывает события выполнения, поступающие от преобразователя. |
| [isEmpty()](#isEmpty--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(System.Delegate arg0, System.Delegate arg1)](#op-Equality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)](#op-Equality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-) |  |
| [op_Inequality(System.Delegate arg0, System.Delegate arg1)](#op-Inequality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)](#op-Inequality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-) |  |
| [peekOutRefParam(int arg0)](#peekOutRefParam-int-) |  |
| [peekResult()](#peekResult--) |  |
| [remove(System.Delegate arg0, System.Delegate arg1)](#remove-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [removeAll(System.Delegate arg0, System.Delegate arg1)](#removeAll-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [setException(RuntimeException arg0)](#setException-java.lang.RuntimeException-) |  |
| [throwException()](#throwException--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ConversionProgressEventHandler() {#ConversionProgressEventHandler--}
```
public ConversionProgressEventHandler()
```


### beginInvoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo, System.AsyncCallback callback, Object state)
```


внутренний метод

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventInfo | [ProgressEventHandlerInfo](../../com.aspose.pdf/progresseventhandlerinfo) | внутренний объект |
| callback | com.aspose.ms.System.AsyncCallback | внутренний объект |
| state | java.lang.Object | внутренний объект |

**Возвращает:**
com.aspose.ms.System.IAsyncResult — внутренний объект
### combine(System.Delegate arg0, System.Delegate arg1) {#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate combine(System.Delegate arg0, System.Delegate arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Возвращает:**
com.aspose.ms.System.Delegate
### combine(System.Delegate[] arg0) {#combine-com.aspose.ms.System.Delegate...-}
```
public static System.Delegate combine(System.Delegate[] arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate[] |  |

**Возвращает:**
com.aspose.ms.System.Delegate
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```


внутренний метод

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | внутренний объект |

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
### getInvocationList() {#getInvocationList--}
```
public final System.Delegate[] getInvocationList()
```




**Возвращает:**
com.aspose.ms.System.Delegate[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### invoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {#invoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-}
```
public abstract void invoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo)
```


Представляет класс с абстрактным методом, который обычно предоставляется вызывающей стороной, и обрабатывает события выполнения, поступающие от преобразователя. Обычно такой предоставленный обработчик клиента может использоваться для отображения общего прогресса преобразования на консоли или в строке выполнения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventInfo | [ProgressEventHandlerInfo](../../com.aspose.pdf/progresseventhandlerinfo) | представляет информацию о произошедшем событии прогресса |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




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




### op_Equality(System.Delegate arg0, System.Delegate arg1) {#op-Equality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static boolean op_Equality(System.Delegate arg0, System.Delegate arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Возвращает:**
логический
### op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Equality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**Возвращает:**
логический
### op_Inequality(System.Delegate arg0, System.Delegate arg1) {#op-Inequality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static boolean op_Inequality(System.Delegate arg0, System.Delegate arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Возвращает:**
логический
### op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Inequality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**Возвращает:**
логический
### peekOutRefParam(int arg0) {#peekOutRefParam-int-}
```
public Object peekOutRefParam(int arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | int |  |

**Возвращает:**
java.lang.Объект
### peekResult() {#peekResult--}
```
public Object peekResult()
```




**Возвращает:**
java.lang.Объект
### remove(System.Delegate arg0, System.Delegate arg1) {#remove-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate remove(System.Delegate arg0, System.Delegate arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Возвращает:**
com.aspose.ms.System.Delegate
### removeAll(System.Delegate arg0, System.Delegate arg1) {#removeAll-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate removeAll(System.Delegate arg0, System.Delegate arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Возвращает:**
com.aspose.ms.System.Delegate
### setException(RuntimeException arg0) {#setException-java.lang.RuntimeException-}
```
public void setException(RuntimeException arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.RuntimeException |  |

### throwException() {#throwException--}
```
public void throwException()
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
