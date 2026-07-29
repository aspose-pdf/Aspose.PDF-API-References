---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Aspose.PDF for Java API 参考"
description: "度量的数字格式。"
type: docs
weight: 2940
url: /zh/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

度量的数字格式。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | NumberFormat 类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAfterText](#getAfterText--) | 标签后应连接的文本 |
| [getBeforeText](#getBeforeText--) | 标签左侧应连接的文本。 |
| [getConvresionFactor](#getConvresionFactor--) | 用于将前一个数字格式数组元素的部分单位值相乘的转换因子，以获得此数字格式单位的值。 |
| [getDenominator](#getDenominator--) | 如果 FractionDisplayment 为 ShowAsFraction，则此值为分数的分母。默认值为 16。 |
| [getFractionDisplayment](#getFractionDisplayment--) | 分数值的显示方式。 |
| [getFractionSeparator](#getFractionSeparator--) | 用于在显示数值时作为小数位的文本。空字符串表示使用默认值。默认是句点字符。 |
| [getPrecision](#getPrecision--) | 如果 FractionDisplayment 为 ShowAsDecimal，则此值为分数值的精度；它应为 10 的倍数。默认值为 100。 |
| [getThousandsSeparator](#getThousandsSeparator--) | 用于在显示数值时千位分隔的文本。空字符串表示不添加任何文本。默认是逗号。 |
| [getUnitLabel](#getUnitLabel--) | 指定用于显示单位的标签的文本字符串。 |
| [isForceDenominator](#isForceDenominator--) | 如果 FractionDisplayment 为 ShowAsFraction，此值决定是否对分数进行约简。如果值为 true，则分数可能不被约简。 |
| [setAfterText](#setAfterText-java.lang.String-) | 标签后应连接的文本 |
| [setBeforeText](#setBeforeText-java.lang.String-) | 标签左侧应连接的文本。 |
| [setConvresionFactor](#setConvresionFactor-double-) | 用于将前一个数字格式数组元素的部分单位值相乘的转换因子，以获得此数字格式单位的值。 |
| [setDenominator](#setDenominator-int-) | 如果 FractionDisplayment 为 ShowAsFraction，则此值为分数的分母。默认值为 16。 |
| [setForceDenominator](#setForceDenominator-boolean-) | 如果 FractionDisplayment 为 ShowAsFraction，此值决定是否对分数进行约简。如果值为 true，则分数可能不被约简。 |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | 分数值的显示方式。 |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | 用于在显示数值时作为小数位的文本。空字符串表示使用默认值。默认是句点字符。 |
| [setPrecision](#setPrecision-int-) | 如果 FractionDisplayment 为 ShowAsDecimal，则此值为分数值的精度；它应为 10 的倍数。默认值为 100。 |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | 用于在显示数值时千位分隔的文本。空字符串表示不添加任何文本。默认是逗号。 |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
NumberFormat 类的构造函数。

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

标签后应连接的文本

**Returns:**
字符串对象

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

标签左侧应连接的文本。

**Returns:**
字符串对象

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

用于将前一个数字格式数组元素的部分单位值相乘的转换因子，以获得此数字格式单位的值。

**Returns:**
double 值

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

如果 FractionDisplayment 为 ShowAsFraction，则此值为分数的分母。默认值为 16。

**Returns:**
int 值

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

分数值的显示方式。

**Returns:**
FractionStyle 值 @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

用于在显示数值时作为小数位的文本。空字符串表示使用默认值。默认是句点字符。

**Returns:**
字符串值

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

如果 FractionDisplayment 为 ShowAsDecimal，则此值为分数值的精度；它应为 10 的倍数。默认值为 100。

**Returns:**
int 值

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

用于在显示数值时千位分隔的文本。空字符串表示不添加任何文本。默认是逗号。

**Returns:**
字符串值

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

指定用于显示单位的标签的文本字符串。

**Returns:**
字符串对象

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

如果 FractionDisplayment 为 ShowAsFraction，此值决定是否对分数进行约简。如果值为 true，则分数可能不被约简。

**Returns:**
布尔值

### setAfterText {#setAfterText-java.lang.String-}
标签后应连接的文本

### setBeforeText {#setBeforeText-java.lang.String-}
标签左侧应连接的文本。

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

用于将前一个数字格式数组元素的部分单位值相乘的转换因子，以获得此数字格式单位的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

如果 FractionDisplayment 为 ShowAsFraction，则此值为分数的分母。默认值为 16。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

如果 FractionDisplayment 为 ShowAsFraction，此值决定是否对分数进行约简。如果值为 true，则分数可能不被约简。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
分数值的显示方式。

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
用于在显示数值时作为小数位的文本。空字符串表示使用默认值。默认是句点字符。

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

如果 FractionDisplayment 为 ShowAsDecimal，则此值为分数值的精度；它应为 10 的倍数。默认值为 100。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
用于在显示数值时千位分隔的文本。空字符串表示不添加任何文本。默认是逗号。

### setUnitLabel {#setUnitLabel-java.lang.String-}
