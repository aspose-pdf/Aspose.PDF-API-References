---
title: HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF для справки по Java API
description: Вы можете назначить этому свойству пользовательскую стратегию, реализующую обработку и/или сохранение одной части CSS, созданной при конвертации PDF в HTML.
type: docs
weight: 12
url: /ru/java/com.aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.CssSavingStrategy extends System.MulticastDelegate
```

Вы можете назначить этому свойству пользовательскую стратегию, реализующую обработку и/или сохранение одной части CSS, созданной при конвертации PDF в HTML. В этом случае обработка (например, сохранение в поток или на диск) должна выполняться в этом пользовательском коде.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CssSavingStrategy()](#CssSavingStrategy--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [beginInvoke(HtmlSaveOptions.CssSavingInfo partSavingInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [combine(System.Delegate arg0, System.Delegate arg1)](#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [combine(System.Delegate[] arg0)](#combine-com.aspose.ms.System.Delegate...-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getInvocationList()](#getInvocationList--) |  |
| [hashCode()](#hashCode--) |  |
| [invoke(HtmlSaveOptions.CssSavingInfo partSavingInfo)](#invoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-) |  |
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
### CssSavingStrategy() {#CssSavingStrategy--}
```
public CssSavingStrategy()
```


### beginInvoke(HtmlSaveOptions.CssSavingInfo partSavingInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(HtmlSaveOptions.CssSavingInfo partSavingInfo, System.AsyncCallback callback, Object state)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| partSavingInfo | [CssSavingInfo](../../com.aspose.pdf/csssavinginfo) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Возвращает:**
com.aspose.ms.System.IAsyncResult
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




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

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
### invoke(HtmlSaveOptions.CssSavingInfo partSavingInfo) {#invoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-}
```
public abstract void invoke(HtmlSaveOptions.CssSavingInfo partSavingInfo)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| partSavingInfo | [CssSavingInfo](../../com.aspose.pdf/csssavinginfo) |  |

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
