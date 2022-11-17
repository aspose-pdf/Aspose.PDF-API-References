---
title: ReplaceTextStrategy
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类包含在执行 ReplaceText 操作时定义 PdfContentEditor 行为的参数。
type: docs
weight: 57
url: /zh/java/com.aspose.pdf.facades/replacetextstrategy/
---
**遗产：**
java.lang.Object
```
public final class ReplaceTextStrategy
```

此类包含在执行 ReplaceText 操作时定义 PdfContentEditor 行为的参数。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ReplaceTextStrategy()](#ReplaceTextStrategy--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | 当没有为更改的文本找到合适的字体时执行的操作（抛出异常/替换其他字体/无论如何替换）。 |
| [getReplaceScope()](#getReplaceScope--) | 替换操作的范围（替换第一次出现或替换所有出现）。 |
| [hashCode()](#hashCode--) |  |
| [isRegularExpressionUsed()](#isRegularExpressionUsed--) | 如果为假，则要查找的字符串是一个简单的文本。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | 当没有为更改的文本找到合适的字体时执行的操作（抛出异常/替换其他字体/无论如何替换）。 |
| [setRegularExpressionUsed(boolean value)](#setRegularExpressionUsed-boolean-) | 如果为假，则要查找的字符串是一个简单的文本。 |
| [setReplaceScope(int value)](#setReplaceScope-int-) | 替换操作的范围（替换第一次出现或替换所有出现）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReplaceTextStrategy() {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```


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
### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


当没有为更改的文本找到合适的字体时执行的操作（抛出异常/替换其他字体/无论如何替换）。

**退货：**
int - NoCharacterAction 值。
### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


替换操作的范围（替换第一次出现或替换所有出现）。

**退货：**
int - 作用域元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isRegularExpressionUsed() {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```


如果为假，则要查找的字符串是一个简单的文本。如果为真，则要查找的字符串是正则表达式。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```


当没有为更改的文本找到合适的字体时执行的操作（抛出异常/替换其他字体/无论如何替换）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | NoCharacterAction 值。 |

### setRegularExpressionUsed(boolean value) {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```


如果为假，则要查找的字符串是一个简单的文本。如果为真，则要查找的字符串是正则表达式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


替换操作的范围（替换第一次出现或替换所有出现）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

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
