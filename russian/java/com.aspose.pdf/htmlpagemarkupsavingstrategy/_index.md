---
title: HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF для справки по Java API
description: Результат конвертации может содержать одну или несколько HTML-страниц, которые также могут ссылаться на внешние файлы, такие как изображения или шрифты. Этому свойству можно присвоить делегат, созданный из пользовательского метода, реализующего обработку полученной HTML-страницы, самой HTML-страницы, созданной при конвертации.
type: docs
weight: 21
url: /ru/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends System.MulticastDelegate
```

Результат преобразования может содержать одну или несколько HTML-страниц (которые также могут ссылаться на внешние файлы, такие как изображения или шрифты). Вы можете присвоить этому свойству делегат, созданный из пользовательского метода, который реализует обработку полученной HTML-страницы (собственно HTML), созданной во время преобразование. В этом случае обработка (например, сохранение в потоке или на диске) может выполняться в этом пользовательском коде. В этом случае все необходимые действия по сохранению разметки HTML-страницы должны быть выполнены в коде предоставленного метода, т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка в том или ином случае по каким-либо причинам должна производиться самим кодом конвертера, а не в пользовательском коде, пожалуйста, установите в пользовательском коде флаг CustomProcessingCancelled переменной параметра htmlSavingInfo: он сигнализирует конвертеру, что все необходимые шаги для обработки этого ресурса должно быть сделано в самом конвертере так же, как если бы не было никакого внешнего пользовательского кода сохранения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlPageMarkupSavingStrategy()](#HtmlPageMarkupSavingStrategy--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [beginInvoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Внутренний метод beginInvoke |
| [combine(System.Delegate arg0, System.Delegate arg1)](#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [combine(System.Delegate[] arg0)](#combine-com.aspose.ms.System.Delegate...-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Внутренний метод endInvoke |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getInvocationList()](#getInvocationList--) |  |
| [hashCode()](#hashCode--) |  |
| [invoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo)](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Вызванный метод |
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
### HtmlPageMarkupSavingStrategy() {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```


### beginInvoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo, System.AsyncCallback callback, Object state)
```


Внутренний метод beginInvoke

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlSavingInfo | [HtmlPageMarkupSavingInfo](../../com.aspose.pdf/htmlpagemarkupsavinginfo) | Объект SaveOptions.ResourceSavingInfo |
| callback | com.aspose.ms.System.AsyncCallback | Объект AsyncCallback |
| state | java.lang.Object | государственный объект |

**Возвращает:**
com.aspose.ms.System.IAsyncResult — объект IAsyncResult
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


Внутренний метод endInvoke

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | Объект IAsyncResult |

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
### invoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo) {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
```
public abstract void invoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo)
```


Вызванный метод

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlSavingInfo | [HtmlPageMarkupSavingInfo](../../com.aspose.pdf/htmlpagemarkupsavinginfo) | Объект SaveOptions.ResourceSavingInfo |

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
