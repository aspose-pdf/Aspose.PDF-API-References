---
title: SystemFontsSubstitution
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示字体替换策略的类，该策略将字体替换为系统字体。
type: docs
weight: 19
url: /zh/java/com.aspose.pdf.text/systemfontssubstitution/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public final class SystemFontsSubstitution extends FontSubstitution
```

表示字体替换策略的类，该策略将字体替换为系统字体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SystemFontsSubstitution(int fontCategories)](#SystemFontsSubstitution-int-) | 初始化 SystemFontsSubstitution 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 获取或设置默认替换字体。 |
| [getFontCategories()](#getFontCategories--) | 获取或设置应替换为系统字体的替换字体类别。 |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | 返回 unicode 替换 |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | 获取替换字体定义 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(Font value)](#setDefaultFont-com.aspose.pdf.Font-) | 获取或设置默认替换字体。 |
| [setFontCategories(int value)](#setFontCategories-int-) | 获取或设置应替换为系统字体的替换字体类别。 |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | 设置替换字体定义 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SystemFontsSubstitution(int fontCategories) {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```


初始化 SystemFontsSubstitution 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontCategories | int | 目标字体类别以替换为系统字体 |

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
### getDefaultFont() {#getDefaultFont--}
```
public Font getDefaultFont()
```


获取或设置默认替换字体。当未找到其他有效替换但初始字体属于目标替换类别 (FontCategories) 时使用该字体。

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象
### getFontCategories() {#getFontCategories--}
```
public int getFontCategories()
```


获取或设置应替换为系统字体的替换字体类别。

**退货：**
int - SubstitutionFontCategories 元素
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




### setDefaultFont(Font value) {#setDefaultFont-com.aspose.pdf.Font-}
```
public void setDefaultFont(Font value)
```


获取或设置默认替换字体。当未找到其他有效替换但初始字体属于目标替换类别 (FontCategories) 时使用该字体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | 字体对象 |

### setFontCategories(int value) {#setFontCategories-int-}
```
public void setFontCategories(int value)
```


获取或设置应替换为系统字体的替换字体类别。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | SubstitutionFontCategories 元素 |

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
