---
title: TextReplaceOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本替换选项
type: docs
weight: 384
url: /zh/java/com.aspose.pdf/textreplaceoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextReplaceOptions extends TextOptions
```

表示文本替换选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextReplaceOptions(int scope)](#TextReplaceOptions-int-) | 为指定范围初始化 TextReplaceOptions 对象的新实例。 |
| [TextReplaceOptions(int adjustment, int scope)](#TextReplaceOptions-int-int-) | 为指定的替换后操作初始化 TextReplaceOptions 对象的新实例。 |
| [TextReplaceOptions()](#TextReplaceOptions--) | 为默认调整和范围初始化 TextReplaceOptions 对象的新实例：ReplaceAdjustment.None 和 Scope.REPLACE\_第一的 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdjustmentNewLineSpacing()](#getAdjustmentNewLineSpacing--) | 获取或设置在强制替换调整以创建新文本行时使用的行距值。 |
| [getClass()](#getClass--) |  |
| [getReplaceAdjustmentAction()](#getReplaceAdjustmentAction--) | 获取将文本片段替换为更短后将完成的操作。 |
| [getReplaceScope()](#getReplaceScope--) | 获取应用替换文本操作的范围 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdjustmentNewLineSpacing(double value)](#setAdjustmentNewLineSpacing-double-) | 获取或设置在强制替换调整以创建新文本行时使用的行距值。 |
| [setReplaceAdjustmentAction(int value)](#setReplaceAdjustmentAction-int-) | 将替换文本片段后将执行的操作设置为更短。 |
| [setReplaceScope(int value)](#setReplaceScope-int-) | 设置应用替换文本操作的范围 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextReplaceOptions(int scope) {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int scope)
```


为指定范围初始化 TextReplaceOptions 对象的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| scope | int | 范围对象。 |

### TextReplaceOptions(int adjustment, int scope) {#TextReplaceOptions-int-int-}
```
public TextReplaceOptions(int adjustment, int scope)
```


为指定的替换后操作初始化 TextReplaceOptions 对象的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| adjustment | int | 替换调整对象。 |
| scope | int | 范围对象。 |

### TextReplaceOptions() {#TextReplaceOptions--}
```
public TextReplaceOptions()
```


为默认调整和范围初始化 TextReplaceOptions 对象的新实例：ReplaceAdjustment.None 和 Scope.REPLACE\_第一的

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
### getAdjustmentNewLineSpacing() {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```


获取或设置在强制替换调整以创建新文本行时使用的行距值。预期值是替换文本的字体大小的倍数。默认值为 1.2。

**退货：**
双倍价值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getReplaceAdjustmentAction() {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```


获取将文本片段替换为更短后将完成的操作。

**退货：**
int - ReplaceAdjustment 元素
### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


获取应用替换文本操作的范围

**退货：**
int - 整数值
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




### setAdjustmentNewLineSpacing(double value) {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```


获取或设置在强制替换调整以创建新文本行时使用的行距值。预期值是替换文本的字体大小的倍数。默认值为 1.2。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setReplaceAdjustmentAction(int value) {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```


将替换文本片段后将执行的操作设置为更短。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 替换调整元素 |

### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


设置应用替换文本操作的范围

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
