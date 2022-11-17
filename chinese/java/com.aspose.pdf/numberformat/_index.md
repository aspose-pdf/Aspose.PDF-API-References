---
title: Measure.NumberFormat
second_title: 用于 Java API 参考的 Aspose.PDF
description: 度量的数字格式。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf/measure.numberformat/
---
**遗产：**
java.lang.Object
```
public static class Measure.NumberFormat
```

度量的数字格式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NumberFormat(Measure measure)](#NumberFormat-com.aspose.pdf.Measure-) | NumberFormat 类的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterText()](#getAfterText--) | 标签后应连接的文本 |
| [getBeforeText()](#getBeforeText--) | 应连接到标签左侧的文本。 |
| [getClass()](#getClass--) |  |
| [getConvresionFactor()](#getConvresionFactor--) | 转换因子，用于乘以前一个数字格式数组元素的部分单位值，以获得此数字格式单位的值。 |
| [getDenominator()](#getDenominator--) | 如果 FractionDisplayment 是 ShowAsFraction，则此值为分数的分母。 |
| [getFractionDisplayment()](#getFractionDisplayment--) | 分数值以何种方式显示。 |
| [getFractionSeparator()](#getFractionSeparator--) | 在显示数值时应用作小数位的文本。 |
| [getPrecision()](#getPrecision--) | 如果FractionDisplayment是ShowAsDecimal，这个值是小数值的精度；它应该是 10 的倍数。 |
| [getThousandsSeparator()](#getThousandsSeparator--) | 在显示数值时应在千位之间使用的文本。 |
| [getUnitLabel()](#getUnitLabel--) | 指定用于显示单位的标签的文本字符串。 |
| [hashCode()](#hashCode--) |  |
| [isForceDenominator()](#isForceDenominator--) | 如果 FractionDisplayment 是 ShowAsFraction，则此值决定是否减少分数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterText(String value)](#setAfterText-java.lang.String-) | 标签后应连接的文本 |
| [setBeforeText(String value)](#setBeforeText-java.lang.String-) | 应连接到标签左侧的文本。 |
| [setConvresionFactor(double value)](#setConvresionFactor-double-) | 转换因子，用于乘以前一个数字格式数组元素的部分单位值，以获得此数字格式单位的值。 |
| [setDenominator(int value)](#setDenominator-int-) | 如果 FractionDisplayment 是 ShowAsFraction，则此值为分数的分母。 |
| [setForceDenominator(boolean value)](#setForceDenominator-boolean-) | 如果 FractionDisplayment 是 ShowAsFraction，则此值决定是否减少分数。 |
| [setFractionDisplayment(int value)](#setFractionDisplayment-int-) | 分数值以何种方式显示。 |
| [setFractionSeparator(String value)](#setFractionSeparator-java.lang.String-) | 在显示数值时应用作小数位的文本。 |
| [setPrecision(int value)](#setPrecision-int-) | 如果FractionDisplayment是ShowAsDecimal，这个值是小数值的精度；它应该是 10 的倍数。 |
| [setThousandsSeparator(String value)](#setThousandsSeparator-java.lang.String-) | 在显示数值时应在千位之间使用的文本。 |
| [setUnitLabel(String value)](#setUnitLabel-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NumberFormat(Measure measure) {#NumberFormat-com.aspose.pdf.Measure-}
```
public NumberFormat(Measure measure)
```


NumberFormat 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| measure | [Measure](../../com.aspose.pdf/measure) | 包含此数字格式的度量对象。 |

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
### getAfterText() {#getAfterText--}
```
public String getAfterText()
```


标签后应连接的文本

**退货：**
java.lang.String - 字符串对象
### getBeforeText() {#getBeforeText--}
```
public String getBeforeText()
```


应连接到标签左侧的文本。

**退货：**
java.lang.String - 字符串对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getConvresionFactor() {#getConvresionFactor--}
```
public double getConvresionFactor()
```


转换因子，用于乘以前一个数字格式数组元素的部分单位值，以获得此数字格式单位的值。

**退货：**
双倍价值
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


如果 FractionDisplayment 是 ShowAsFraction，则此值为分数的分母。默认值为 16。

**退货：**
int - 整数值
### getFractionDisplayment() {#getFractionDisplayment--}
```
public int getFractionDisplayment()
```


分数值以何种方式显示。

**退货：**
int - FractionStyle 值
### getFractionSeparator() {#getFractionSeparator--}
```
public String getFractionSeparator()
```


在显示数值时应用作小数位的文本。空字符串表示应使用默认值。默认为句点字符。

**退货：**
java.lang.String - 字符串值
### getPrecision() {#getPrecision--}
```
public int getPrecision()
```


如果FractionDisplayment是ShowAsDecimal，这个值是小数值的精度；它应为 10 的倍数。默认值为 100。

**退货：**
int - 整数值
### getThousandsSeparator() {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```


在显示数值时应在千位之间使用的文本。空字符串表示不应添加任何文本。默认为逗号。

**退货：**
java.lang.String - 字符串值
### getUnitLabel() {#getUnitLabel--}
```
public String getUnitLabel()
```


指定用于显示单位的标签的文本字符串。

**退货：**
java.lang.String - 字符串对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isForceDenominator() {#isForceDenominator--}
```
public boolean isForceDenominator()
```


如果 FractionDisplayment 是 ShowAsFraction，则此值决定是否减少分数。如果值为真，分数可能不会减少。

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




### setAfterText(String value) {#setAfterText-java.lang.String-}
```
public void setAfterText(String value)
```


标签后应连接的文本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setBeforeText(String value) {#setBeforeText-java.lang.String-}
```
public void setBeforeText(String value)
```


应连接到标签左侧的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setConvresionFactor(double value) {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```


转换因子，用于乘以前一个数字格式数组元素的部分单位值，以获得此数字格式单位的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setDenominator(int value) {#setDenominator-int-}
```
public void setDenominator(int value)
```


如果 FractionDisplayment 是 ShowAsFraction，则此值为分数的分母。默认值为 16。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setForceDenominator(boolean value) {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```


如果 FractionDisplayment 是 ShowAsFraction，则此值决定是否减少分数。如果值为真，分数可能不会减少。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFractionDisplayment(int value) {#setFractionDisplayment-int-}
```
public void setFractionDisplayment(int value)
```


分数值以何种方式显示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | FractionStyle 值 |

### setFractionSeparator(String value) {#setFractionSeparator-java.lang.String-}
```
public void setFractionSeparator(String value)
```


在显示数值时应用作小数位的文本。空字符串表示应使用默认值。默认为句点字符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setPrecision(int value) {#setPrecision-int-}
```
public void setPrecision(int value)
```


如果FractionDisplayment是ShowAsDecimal，这个值是小数值的精度；它应为 10 的倍数。默认值为 100。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setThousandsSeparator(String value) {#setThousandsSeparator-java.lang.String-}
```
public void setThousandsSeparator(String value)
```


在显示数值时应在千位之间使用的文本。空字符串表示不应添加任何文本。默认为逗号。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setUnitLabel(String value) {#setUnitLabel-java.lang.String-}
```
public void setUnitLabel(String value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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
