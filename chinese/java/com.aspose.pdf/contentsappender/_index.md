---
title: ContentsAppender
second_title: 用于 Java API 参考的 Aspose.PDF
description: 仅在 APPEND 模式下执行内容修改。
type: docs
weight: 73
url: /zh/java/com.aspose.pdf/contentsappender/
---
**遗产：**
java.lang.Object
```
public class ContentsAppender
```

仅在 APPEND 模式下执行内容修改。这种模式允许在对内容进行某些更改之前避免不必要的和繁重的内容解析。它仅将新运算符附加到内容的末尾或开头
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ContentsAppender(Page page)](#ContentsAppender-com.aspose.pdf.Page-) | 初始化带有附加页面的内容附加器的新实例 |
| [ContentsAppender(XForm form)](#ContentsAppender-com.aspose.pdf.XForm-) | 使用 Form XObject 初始化 contets appender 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [appendToBegin(System.Collections.Generic.List<Operator> operators)](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | 将运算符附加到内容的末尾 |
| [appendToBegin(Operator op)](#appendToBegin-com.aspose.pdf.Operator-) | 将运算符附加到内容的末尾 |
| [appendToBegin(Operator[] operators)](#appendToBegin-com.aspose.pdf.Operator---) | 将运算符附加到内容的末尾 |
| [appendToEnd(System.Collections.Generic.List<Operator> operators)](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | 将运算符附加到内容的开头 |
| [appendToEnd(Operator op)](#appendToEnd-com.aspose.pdf.Operator-) | 将运算符附加到内容的开头 |
| [appendToEnd(Operator[] operators)](#appendToEnd-com.aspose.pdf.Operator---) | 将运算符附加到内容的开头 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginCode()](#getBeginCode--) | 包含要插入到页首的运算符的字符串。 |
| [getBeginOperators()](#getBeginOperators--) | 返回开始运算符 |
| [getClass()](#getClass--) |  |
| [getEndCode()](#getEndCode--) | Stirng 包含要追加到页面末尾的运算符。 |
| [getEndOperators()](#getEndOperators--) | 返回结束运算符 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resumeUpdate()](#resumeUpdate--) | 恢复文档更新 |
| [setBeginCode(String value)](#setBeginCode-java.lang.String-) | 包含要插入到页首的运算符的字符串。 |
| [setEndCode(String value)](#setEndCode-java.lang.String-) | 包含要插入到页首的运算符的字符串。 |
| [suppressUpdate()](#suppressUpdate--) | 禁止更新内容数据内容不会更新，直到调用 ResumeUpdate |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | 这是 UpdateData 的新版本，它避免了对现有内容的解码。 |
| [updateDataOld()](#updateDataOld--) | 必须调用以应用更改 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentsAppender(Page page) {#ContentsAppender-com.aspose.pdf.Page-}
```
public ContentsAppender(Page page)
```


初始化带有附加页面的内容附加器的新实例

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |

### ContentsAppender(XForm form) {#ContentsAppender-com.aspose.pdf.XForm-}
```
public ContentsAppender(XForm form)
```


使用 Form XObject 初始化 contets appender 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | 变形对象 |

### appendToBegin(System.Collections.Generic.List<Operator> operators) {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public void appendToBegin(System.Collections.Generic.List<Operator> operators)
```


将运算符附加到内容的末尾

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> |  列表对象 |

### appendToBegin(Operator op) {#appendToBegin-com.aspose.pdf.Operator-}
```
public void appendToBegin(Operator op)
```


将运算符附加到内容的末尾

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 运算符对象 |

### appendToBegin(Operator[] operators) {#appendToBegin-com.aspose.pdf.Operator---}
```
public void appendToBegin(Operator[] operators)
```


将运算符附加到内容的末尾

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | 运算符数组 |

### appendToEnd(System.Collections.Generic.List<Operator> operators) {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public void appendToEnd(System.Collections.Generic.List<Operator> operators)
```


将运算符附加到内容的开头

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> |  列表对象 |

### appendToEnd(Operator op) {#appendToEnd-com.aspose.pdf.Operator-}
```
public void appendToEnd(Operator op)
```


将运算符附加到内容的开头

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 运算符对象 |

### appendToEnd(Operator[] operators) {#appendToEnd-com.aspose.pdf.Operator---}
```
public void appendToEnd(Operator[] operators)
```


将运算符附加到内容的开头

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | 运算符数组 |

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
### getBeginCode() {#getBeginCode--}
```
public String getBeginCode()
```


包含要插入到页首的运算符的字符串。

**退货：**
java.lang.String - 字符串对象
### getBeginOperators() {#getBeginOperators--}
```
public System.Collections.Generic.List<Operator> getBeginOperators()
```


返回开始运算符

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - 列表对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEndCode() {#getEndCode--}
```
public String getEndCode()
```


Stirng 包含要追加到页面末尾的运算符。

**退货：**
java.lang.String - 字符串对象
### getEndOperators() {#getEndOperators--}
```
public System.Collections.Generic.List<Operator> getEndOperators()
```


返回结束运算符

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - 列表对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


恢复文档更新

### setBeginCode(String value) {#setBeginCode-java.lang.String-}
```
public void setBeginCode(String value)
```


包含要插入到页首的运算符的字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setEndCode(String value) {#setEndCode-java.lang.String-}
```
public void setEndCode(String value)
```


包含要插入到页首的运算符的字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


禁止更新内容数据内容不会更新，直到调用 ResumeUpdate

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### updateData() {#updateData--}
```
public void updateData()
```


这是 UpdateData 的新版本，它避免了对现有内容的解码。

### updateDataOld() {#updateDataOld--}
```
public void updateDataOld()
```


必须调用以应用更改

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
