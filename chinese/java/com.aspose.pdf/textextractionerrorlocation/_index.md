---
title: TextExtractionErrorLocation
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PDF 文档中出现文本提取错误的位置。
type: docs
weight: 369
url: /zh/java/com.aspose.pdf/textextractionerrorlocation/
---
**遗产：**
java.lang.Object
```
public final class TextExtractionErrorLocation
```

表示 PDF 文档中出现文本提取错误的位置。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFontUsedKey()](#getFontUsedKey--) | 用于显示导致文本提取错误的运算符的 PDF 字体对象的键（名称）。 |
| [getFormKey()](#getFormKey--) | 内容流文本提取错误所在的 PDF 表单 XObject 的键（名称）。 |
| [getObjectType()](#getObjectType--) | 内容流文本提取错误所在的 PDF 对象（Page 或 xForm）的类型。 |
| [getOperatorIndex()](#getOperatorIndex--) | 显示内容流（运算符集合）中导致文本提取错误的运算符的文本索引。 |
| [getOperatorString()](#getOperatorString--) | 导致文本提取错误的文本显示运算符。 |
| [getPageNumber()](#getPageNumber--) | 文本提取错误所在的文档页码。 |
| [getPath()](#getPath--) | 出现文本提取错误的 PDF 文档的位置。 |
| [getTextStartPoint()](#getTextStartPoint--) | 用于显示导致文本提取错误的运算符的 PDF 字体对象的键（名称）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getFontUsedKey() {#getFontUsedKey--}
```
public String getFontUsedKey()
```


用于显示导致文本提取错误的运算符的 PDF 字体对象的键（名称）。

**退货：**
java.lang.String - 字符串值
### getFormKey() {#getFormKey--}
```
public String getFormKey()
```


内容流文本提取错误所在的 PDF 表单 XObject 的键（名称）。如果 ObjectType == 'xForm' 则不为空。

**退货：**
java.lang.String - 字符串值
### getObjectType() {#getObjectType--}
```
public String getObjectType()
```


内容流文本提取错误所在的 PDF 对象（Page 或 xForm）的类型。

**退货：**
java.lang.String - 字符串值
### getOperatorIndex() {#getOperatorIndex--}
```
public int getOperatorIndex()
```


显示内容流（运算符集合）中导致文本提取错误的运算符的文本索引。

**退货：**
int - 整数值
### getOperatorString() {#getOperatorString--}
```
public String getOperatorString()
```


导致文本提取错误的文本显示运算符。

**退货：**
java.lang.String - 字符串值
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


文本提取错误所在的文档页码。

**退货：**
int - 整数值
### getPath() {#getPath--}
```
public String getPath()
```


出现文本提取错误的 PDF 文档的位置。

**退货：**
java.lang.String - 字符串值
### getTextStartPoint() {#getTextStartPoint--}
```
public Point getTextStartPoint()
```


用于显示导致文本提取错误的运算符的 PDF 字体对象的键（名称）。

**退货：**
[Point](../../com.aspose.pdf/point) 点实例
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




### toString() {#toString--}
```
public String toString()
```


返回字符串表示。

**退货：**
java.lang.String - 字符串表示。
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
