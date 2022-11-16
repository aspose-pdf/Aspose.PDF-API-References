---
title: SimpleFontSubstitution
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示用于简单字体替换策略的类。
type: docs
weight: 17
url: /zh/java/com.aspose.pdf.text/simplefontsubstitution/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public final class SimpleFontSubstitution extends FontSubstitution
```

表示用于简单字体替换策略的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption)](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | 初始化 SimpleFontSubstitution 类的新实例。 |
| [SimpleFontSubstitution(String originalFontName, String substitutionFontName)](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | 初始化 SimpleFontSubstitution 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalFontName()](#getOriginalFontName--) | 获取应替换为 SubstitutionFontName 的原始字体名称  |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | 返回 unicode 替换 |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | 获取替换字体定义 |
| [getSubstitutionFontName()](#getSubstitutionFontName--) | 获取应替换 OriginalFontName 的字体名称  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | 设置替换字体定义 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption) {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
```
public SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption)
```


初始化 SimpleFontSubstitution 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| originalFontName | java.lang.String | 原始字体名称。 |
| substitutionFontName | java.lang.String | 替换字体名称。 |
| isForcedBySaveOption | boolean | 由 DefaultFontName 保存选项强制替换。 |

### SimpleFontSubstitution(String originalFontName, String substitutionFontName) {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
```
public SimpleFontSubstitution(String originalFontName, String substitutionFontName)
```


初始化 SimpleFontSubstitution 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| originalFontName | java.lang.String | 原始字体名称。 |
| substitutionFontName | java.lang.String | 替换字体名称。 |

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


获取应替换为 SubstitutionFontName 的原始字体名称 

**退货：**
java.lang.String - 字符串值
### getSubstitutedUnicode(char unicode) {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```


返回 unicode 替换

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| unicode | char | 字符值 |

**退货：**
char - 字符值
### getSubstitutionFontDefinition() {#getSubstitutionFontDefinition--}
```
public FontDefinition getSubstitutionFontDefinition()
```


获取替换字体定义

**退货：**
com.aspose.font.FontDefinition - FontDefinition 对象
### getSubstitutionFontName() {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```


获取应替换 OriginalFontName 的字体名称 

**退货：**
java.lang.String - 字符串值
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




### setSubstitutionFontDefinition(FontDefinition value) {#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-}
```
public void setSubstitutionFontDefinition(FontDefinition value)
```


设置替换字体定义

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.font.FontDefinition | 字体定义对象 |

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
