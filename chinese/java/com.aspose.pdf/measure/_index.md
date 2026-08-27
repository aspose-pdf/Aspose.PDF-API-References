---
title: "Measure"
linktitle: "Measure"
second_title: "Aspose.PDF for Java API 参考"
description: "描述 Measure 坐标系的类。"
type: docs
weight: 2930
url: /zh/java/com.aspose.pdf/measure/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure

```
public class Measure extends Object
```

描述 Measure 坐标系的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Measure](#Measure-com.aspose.pdf.Annotation-) | 创建用于测量注释的 Measure 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAngleFormat](#getAngleFormat--) | 用于角度测量的数字格式数组。 |
| [getAreaFormat](#getAreaFormat--) | 用于面积测量的数字格式数组。 |
| [getDistanceFormat](#getDistanceFormat--) | 用于任意方向距离测量的数字格式数组。 |
| [getOrigin](#getOrigin--) | 点，用于指定默认用户空间坐标系中测量坐标系统的原点。 |
| [getScaleRatio](#getScaleRatio--) | 表示图纸比例的文本字符串。 |
| [getSlopeFormat](#getSlopeFormat--) | 用于直线斜率测量的数字格式数组。 |
| [getXFormat](#getXFormat--) | 用于沿 x 轴变化测量的数字格式数组，如果未提供 Y，则也用于沿 y 轴的测量。 |
| [getXYFactor](#getXYFactor--) | 用于将 y 轴的最大单位转换为 x 轴最大单位的因子。 |
| [getYFormat](#getYFormat--) | 用于测量 y 轴变化的数字格式数组。 |
| [setAngleFormat](#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于角度测量的数字格式数组。 |
| [setAreaFormat](#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于面积测量的数字格式数组。 |
| [setDistanceFormat](#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于任意方向距离测量的数字格式数组。 |
| [setOrigin](#setOrigin-com.aspose.pdf.Point-) | 点，用于指定默认用户空间坐标系中测量坐标系统的原点。 |
| [setScaleRatio](#setScaleRatio-java.lang.String-) |  |
| [setSlopeFormat](#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于直线斜率测量的数字格式数组。 |
| [setXFormat](#setXFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于沿 x 轴变化测量的数字格式数组，如果未提供 Y，则也用于沿 y 轴的测量。 |
| [setXYFactor](#setXYFactor-double-) | 用于将 y 轴的最大单位转换为 x 轴最大单位的因子。 |
| [setYFormat](#setYFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于测量 y 轴变化的数字格式数组。 |

### Measure {#Measure-com.aspose.pdf.Annotation-}
创建用于测量注释的 Measure 对象。

### getAngleFormat {#getAngleFormat--}
```
public Measure.NumberFormatList getAngleFormat()
```

用于角度测量的数字格式数组。

**Returns:**
NumberFormatList 值

### getAreaFormat {#getAreaFormat--}
```
public Measure.NumberFormatList getAreaFormat()
```

用于面积测量的数字格式数组。

**Returns:**
NumberFormatList 值

### getDistanceFormat {#getDistanceFormat--}
```
public Measure.NumberFormatList getDistanceFormat()
```

用于任意方向距离测量的数字格式数组。

**Returns:**
NumberFormatList 值

### getOrigin {#getOrigin--}
```
public Point getOrigin()
```

点，用于指定默认用户空间坐标系中测量坐标系统的原点。

**Returns:**
点对象

### getScaleRatio {#getScaleRatio--}
```
public String getScaleRatio()
```

表示图纸比例的文本字符串。

**Returns:**
字符串对象

### getSlopeFormat {#getSlopeFormat--}
```
public Measure.NumberFormatList getSlopeFormat()
```

用于直线斜率测量的数字格式数组。

**Returns:**
NumberFormatList 值

### getXFormat {#getXFormat--}
```
public Measure.NumberFormatList getXFormat()
```

用于沿 x 轴变化测量的数字格式数组，如果未提供 Y，则也用于沿 y 轴的测量。

**Returns:**
NumberFormatList 值

### getXYFactor {#getXYFactor--}
```
public double getXYFactor()
```

用于将 y 轴的最大单位转换为 x 轴最大单位的因子。

**Returns:**
double 值

### getYFormat {#getYFormat--}
```
public Measure.NumberFormatList getYFormat()
```

用于测量 y 轴变化的数字格式数组。

**Returns:**
NumberFormatList 值

### setAngleFormat {#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-}
用于角度测量的数字格式数组。

### setAreaFormat {#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-}
用于面积测量的数字格式数组。

### setDistanceFormat {#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-}
用于任意方向距离测量的数字格式数组。

### setOrigin {#setOrigin-com.aspose.pdf.Point-}
点，用于指定默认用户空间坐标系中测量坐标系统的原点。

### setScaleRatio {#setScaleRatio-java.lang.String-}


### setSlopeFormat {#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-}
用于直线斜率测量的数字格式数组。

### setXFormat {#setXFormat-com.aspose.pdf.Measure.NumberFormatList-}
用于沿 x 轴变化测量的数字格式数组，如果未提供 Y，则也用于沿 y 轴的测量。

### setXYFactor {#setXYFactor-double-}
```
public void setXYFactor(double value)
```

用于将 y 轴的最大单位转换为 x 轴最大单位的因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setYFormat {#setYFormat-com.aspose.pdf.Measure.NumberFormatList-}
用于测量 y 轴变化的数字格式数组。
