---
title: CustomFontSubstitutionBase
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示自定义字体替换策略的基类。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.text/customfontsubstitutionbase/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public class CustomFontSubstitutionBase extends FontSubstitution
```

表示自定义字体替换策略的基类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CustomFontSubstitutionBase()](#CustomFontSubstitutionBase--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | 返回 unicode 替换 |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | 获取替换字体定义 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | 设置替换字体定义 |
| [toString()](#toString--) |  |
| [trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)](#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---) | 用另一种字体替换原始字体。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomFontSubstitutionBase() {#CustomFontSubstitutionBase--}
```
public CustomFontSubstitutionBase()
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
### trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont) {#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---}
```
public boolean trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)
```


用另一种字体替换原始字体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| originalFontSpecification | [OriginalFontSpecification](../../com.aspose.pdf.text/originalfontspecification) | 原始字体规范。 |
| substitutionFont | [Font\[\]](../../com.aspose.pdf/font) | 替换字体。

--------------------

应继承类 CustomFontSubstitutionBase 以实现自定义字体替换逻辑。应正确覆盖 TrySubstitute 方法：如果需要替换，则必须返回 true。 substitutionFont 必须设置为有效的 Font 对象。如果不需要替换，则必须返回 false。 substitutionFont 可以设置为空。|

**退货：**
布尔值 - 如果替换成功则为真。
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
