---
title: CustomFontSubstitutionBase.OriginalFontSpecification
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表原始字体规范。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**遗产：**
java.lang.Object
```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification
```

代表原始字体规范。

--------------------

提供与原始字体相关的信息，例如 , flag。还提供有助于检查字体是否会发生替换的标志，并且用户可以覆盖默认替换逻辑。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable)](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | 初始化新的 OriginalFontSpecification 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalFontName()](#getOriginalFontName--) | 获取原始字体名称。 |
| [hashCode()](#hashCode--) |  |
| [isEmbedded()](#isEmbedded--) | 获取一个值，该值指示是否嵌入字体。 |
| [isSubstitutionUnavoidable()](#isSubstitutionUnavoidable--) | 获取一个值，该值指示替换是不可避免的。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable) {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
```
public OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable)
```


初始化新的 OriginalFontSpecification 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| originalFontName | java.lang.String | 字符串对象 |
| isEmbedded | boolean | 布尔值 |
| isUnavoidable | boolean | 布尔值 |

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
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


获取原始字体名称。

**退货：**
java.lang.String - 字符串值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


获取一个值，该值指示是否嵌入字体。

**退货：**
boolean - 布尔值
### isSubstitutionUnavoidable() {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```


获取一个值，该值指示替换是不可避免的。

**退货：**
boolean - 布尔值

--------------------

如果由于缺少原始字体或原始字体无法在某些任务的上下文中使用而请求替换，则返回 true。如果用户忽略该标志并且不替换字体 - 将执行默认字体替换程序。但它为用户提供了机会来替代标准字体替换过程并为系统设置更好的字体。如果存在原始字体，则返回 false，有效，但允许用户替换它。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
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
