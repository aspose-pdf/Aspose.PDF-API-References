---
title: TextEditOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 描述文本编辑操作的选项。
type: docs
weight: 366
url: /zh/java/com.aspose.pdf/texteditoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextEditOptions extends TextOptions
```

描述文本编辑操作的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) | 使用默认选项初始化 TextEditOptions 对象的新实例。 |
| [TextEditOptions(int noCharacterBehavior)](#TextEditOptions-int-) | 为指定的无字符行为模式初始化 TextEditOptions 对象的新实例。 |
| [TextEditOptions(int option, Class type)](#TextEditOptions-int-java.lang.Class-) | 为指定的无字符行为模式初始化 TextEditOptions 对象的新实例。 |
| [TextEditOptions(boolean allowLanguageTransformation)](#TextEditOptions-boolean-) | 为指定的语言转换权限初始化 TextEditOptions 对象的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowLanguageTransformation()](#getAllowLanguageTransformation--) | 获取允许在添加或编辑文本期间使用语言转换的值。 |
| [getClass()](#getClass--) |  |
| [getClippingPathsProcessing()](#getClippingPathsProcessing--) | 获取用于处理已编辑文本的剪切路径的模式。 |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | 获取定义字体替换方案行为的模式。 |
| [getLanguageTransformationBehavior()](#getLanguageTransformationBehavior--) | 获取定义语言转换场景行为的模式。 |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | 获取定义行为的模式，以防字体不包含请求的字符。 |
| [getReplacementFont()](#getReplacementFont--) | 如果用户字体不包含所需字符，则获取或设置用于替换的字体 |
| [getToAttemptGetUnderlineFromSource()](#getToAttemptGetUnderlineFromSource--) | 获取或设置允许搜索源文档页面上带下划线的文本的值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowLanguageTransformation(boolean value)](#setAllowLanguageTransformation-boolean-) | 设置允许在添加或编辑文本期间使用语言转换的值。 |
| [setClippingPathsProcessing(int value)](#setClippingPathsProcessing-int-) | 获取用于处理已编辑文本的剪切路径的模式。 |
| [setFontReplaceBehavior(int value)](#setFontReplaceBehavior-int-) | 设置定义字体替换方案行为的模式。 |
| [setLanguageTransformationBehavior(int value)](#setLanguageTransformationBehavior-int-) | 设置定义语言转换场景行为的模式。 |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | 设置定义行为的模式，以防字体不包含请求的字符。 |
| [setReplacementFont(Font value)](#setReplacementFont-com.aspose.pdf.Font-) | 如果用户字体不包含所需字符，则获取或设置用于替换的字体 |
| [setToAttemptGetUnderlineFromSource(boolean value)](#setToAttemptGetUnderlineFromSource-boolean-) | 获取或设置允许搜索源文档页面上带下划线的文本的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


使用默认选项初始化 TextEditOptions 对象的新实例。 NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions(int noCharacterBehavior) {#TextEditOptions-int-}
```
public TextEditOptions(int noCharacterBehavior)
```


为指定的无字符行为模式初始化 TextEditOptions 对象的新实例。请使用 setFontReplaceBehavior(int) 初始化 fontReplaceBehavior

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| noCharacterBehavior | int | 无字符行为模式对象。 |

### TextEditOptions(int option, Class type) {#TextEditOptions-int-java.lang.Class-}
```
public TextEditOptions(int option, Class type)
```


为指定的无字符行为模式初始化 TextEditOptions 对象的新实例。请使用 setFontReplaceBehavior(int) 初始化 fontReplaceBehavior

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| option | int | 以下类之一的值：NoCharacterAction、LanguageTransformation、FontReplace、 |
| type | java.lang.Class | 选项类别 |

### TextEditOptions(boolean allowLanguageTransformation) {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```


为指定的语言转换权限初始化 TextEditOptions 对象的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| allowLanguageTransformation | boolean | 如果设置为 true，则允许语言转换。 |

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
### getAllowLanguageTransformation() {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```


获取允许在添加或编辑文本期间使用语言转换的值。 true - 必要时将应用语言转换（默认值）。 false - 不应用语言转换。

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getClippingPathsProcessing() {#getClippingPathsProcessing--}
```
public final int getClippingPathsProcessing()
```


获取用于处理已编辑文本的剪切路径的模式。

**退货：**
int - ClippingPathsProcessingMode 元素
### getFontReplaceBehavior() {#getFontReplaceBehavior--}
```
public int getFontReplaceBehavior()
```


获取定义字体替换方案行为的模式。

**退货：**
int - 字体替换值
### getLanguageTransformationBehavior() {#getLanguageTransformationBehavior--}
```
public int getLanguageTransformationBehavior()
```


获取定义语言转换场景行为的模式。

**退货：**
int - LanguageTransformation 值
### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


获取定义行为的模式，以防字体不包含请求的字符。

**退货：**
int - NoCharacterAction 值
### getReplacementFont() {#getReplacementFont--}
```
public final Font getReplacementFont()
```


如果用户字体不包含所需字符，则获取或设置用于替换的字体

**退货：**
[Font](../../com.aspose.pdf/font) 字体实例
### getToAttemptGetUnderlineFromSource() {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```


获取或设置允许搜索源文档页面上带下划线的文本的值。 （已过时）请改用 TextSearchOptions.SearchForTextRelatedGraphics。

**退货：**
boolean - 布尔值
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




### setAllowLanguageTransformation(boolean value) {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```


设置允许在添加或编辑文本期间使用语言转换的值。 true - 必要时将应用语言转换（默认值）。 false - 不应用语言转换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setClippingPathsProcessing(int value) {#setClippingPathsProcessing-int-}
```
public final void setClippingPathsProcessing(int value)
```


获取用于处理已编辑文本的剪切路径的模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ClippingPathsProcessingMode 元素 |

### setFontReplaceBehavior(int value) {#setFontReplaceBehavior-int-}
```
public void setFontReplaceBehavior(int value)
```


设置定义字体替换方案行为的模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 字体替换值 |

### setLanguageTransformationBehavior(int value) {#setLanguageTransformationBehavior-int-}
```
public void setLanguageTransformationBehavior(int value)
```


设置定义语言转换场景行为的模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 语言转换值 |

### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```


设置定义行为的模式，以防字体不包含请求的字符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | NoCharacterAction 值 |

### setReplacementFont(Font value) {#setReplacementFont-com.aspose.pdf.Font-}
```
public final void setReplacementFont(Font value)
```


如果用户字体不包含所需字符，则获取或设置用于替换的字体

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | 字体实例 |

### setToAttemptGetUnderlineFromSource(boolean value) {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```


获取或设置允许搜索源文档页面上带下划线的文本的值。 （已过时）请改用 TextSearchOptions.SearchForTextRelatedGraphics。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
