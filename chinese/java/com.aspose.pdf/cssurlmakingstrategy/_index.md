---
title: HtmlSaveOptions.CssUrlMakingStrategy
second_title: 用于 Java API 参考的 Aspose.PDF
description: 您可以将此属性委托从自定义方法创建，该方法实现生成的 HTML 文档中引用的 CSS URL 的创建。
type: docs
weight: 13
url: /zh/java/com.aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
**遗产：**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.CssUrlMakingStrategy extends System.MulticastDelegate
```

您可以将此属性委托从自定义方法创建，该方法实现生成的 HTML 文档中引用的 CSS URL 的创建。 Fe 如果你想让 CSS 在 HTML fe 中引用为 "otherPage.ASPX?CssID=zjjkklj" 那么这样的自定义策略必须返回 "otherPage.ASPX?CssID=zjjkklj"
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CssUrlMakingStrategy()](#CssUrlMakingStrategy--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [beginInvoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [combine(System.Delegate arg0, System.Delegate arg1)](#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [combine(System.Delegate[] arg0)](#combine-com.aspose.ms.System.Delegate...-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getInvocationList()](#getInvocationList--) |  |
| [hashCode()](#hashCode--) |  |
| [invoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo)](#invoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-) |  |
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
### CssUrlMakingStrategy() {#CssUrlMakingStrategy--}
```
public CssUrlMakingStrategy()
```


### beginInvoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo, System.AsyncCallback callback, Object state)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cssUrlRequestInfo | [CssUrlRequestInfo](../../com.aspose.pdf/cssurlrequestinfo) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**退货：**
com.aspose.ms.System.IAsyncResult
### combine(System.Delegate arg0, System.Delegate arg1) {#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate combine(System.Delegate arg0, System.Delegate arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**退货：**
com.aspose.ms.System.Delegate
### combine(System.Delegate[] arg0) {#combine-com.aspose.ms.System.Delegate...-}
```
public static System.Delegate combine(System.Delegate[] arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate[] |  |

**退货：**
com.aspose.ms.System.Delegate
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final String endInvoke(System.IAsyncResult result)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | IAsyncResult 对象 |

**退货：**
java.lang.String - 字符串对象
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getInvocationList() {#getInvocationList--}
```
public final System.Delegate[] getInvocationList()
```




**退货：**
com.aspose.ms.System.Delegate[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### invoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo) {#invoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-}
```
public abstract String invoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cssUrlRequestInfo | [CssUrlRequestInfo](../../com.aspose.pdf/cssurlrequestinfo) |  |

**退货：**
java.lang.字符串
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




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**退货：**
布尔值
### op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Equality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**退货：**
布尔值
### op_Inequality(System.Delegate arg0, System.Delegate arg1) {#op-Inequality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static boolean op_Inequality(System.Delegate arg0, System.Delegate arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**退货：**
布尔值
### op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Inequality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**退货：**
布尔值
### peekOutRefParam(int arg0) {#peekOutRefParam-int-}
```
public Object peekOutRefParam(int arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

**退货：**
java.lang.Object
### peekResult() {#peekResult--}
```
public Object peekResult()
```




**退货：**
java.lang.Object
### remove(System.Delegate arg0, System.Delegate arg1) {#remove-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate remove(System.Delegate arg0, System.Delegate arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**退货：**
com.aspose.ms.System.Delegate
### removeAll(System.Delegate arg0, System.Delegate arg1) {#removeAll-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate removeAll(System.Delegate arg0, System.Delegate arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**退货：**
com.aspose.ms.System.Delegate
### setException(RuntimeException arg0) {#setException-java.lang.RuntimeException-}
```
public void setException(RuntimeException arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
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
