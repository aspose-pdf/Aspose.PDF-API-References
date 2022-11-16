---
title: Measure
second_title: 用于 Java API 参考的 Aspose.PDF
description: 描述测量坐标系的类。
type: docs
weight: 212
url: /zh/java/com.aspose.pdf/measure/
---
**遗产：**
java.lang.Object
```
public class Measure
```

描述测量坐标系的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Measure(Annotation annotation)](#Measure-com.aspose.pdf.Annotation-) | 为度量注释创建度量对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngleFormat()](#getAngleFormat--) | 用于测量角度的数字格式数组。 |
| [getAreaFormat()](#getAreaFormat--) | 用于面积测量的数字格式数组。 |
| [getClass()](#getClass--) |  |
| [getDistanceFormat()](#getDistanceFormat--) | 用于测量任意方向距离的数字格式数组。 |
| [getOrigin()](#getOrigin--) | 应在默认用户空间坐标中指定测量坐标系原点的点。 |
| [getScaleRatio()](#getScaleRatio--) | 表示绘图比例的文本字符串。 |
| [getSlopeFormat()](#getSlopeFormat--) | 用于测量直线斜率的数字格式数组。 |
| [getXFormat()](#getXFormat--) | 一个数字格式数组，用于测量沿 x 轴的变化，如果 Y 不存在，则也沿 y 轴 |
| [getXYFactor()](#getXYFactor--) | 一个系数，用于将沿 y 轴的最大单位转换为沿 x 轴的最大单位。 |
| [getYFormat()](#getYFormat--) | 用于测量沿 y 轴变化的数字格式数组。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngleFormat(Measure.NumberFormatList value)](#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于测量角度的数字格式数组。 |
| [setAreaFormat(Measure.NumberFormatList value)](#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于面积测量的数字格式数组。 |
| [setDistanceFormat(Measure.NumberFormatList value)](#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于测量任意方向距离的数字格式数组。 |
| [setOrigin(Point value)](#setOrigin-com.aspose.pdf.Point-) | 应在默认用户空间坐标中指定测量坐标系原点的点。 |
| [setScaleRatio(String value)](#setScaleRatio-java.lang.String-) |  |
| [setSlopeFormat(Measure.NumberFormatList value)](#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于测量直线斜率的数字格式数组。 |
| [setXFormat(Measure.NumberFormatList value)](#setXFormat-com.aspose.pdf.Measure.NumberFormatList-) | 一个数字格式数组，用于测量沿 x 轴的变化，如果 Y 不存在，则也沿 y 轴 |
| [setXYFactor(double value)](#setXYFactor-double-) | 一个系数，用于将沿 y 轴的最大单位转换为沿 x 轴的最大单位。 |
| [setYFormat(Measure.NumberFormatList value)](#setYFormat-com.aspose.pdf.Measure.NumberFormatList-) | 用于测量沿 y 轴变化的数字格式数组。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Measure(Annotation annotation) {#Measure-com.aspose.pdf.Annotation-}
```
public Measure(Annotation annotation)
```


为度量注释创建度量对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 将绑定哪个度量的注释。 |

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
### getAngleFormat() {#getAngleFormat--}
```
public Measure.NumberFormatList getAngleFormat()
```


用于测量角度的数字格式数组。

**退货：**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList 值
### getAreaFormat() {#getAreaFormat--}
```
public Measure.NumberFormatList getAreaFormat()
```


用于面积测量的数字格式数组。

**退货：**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList 值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDistanceFormat() {#getDistanceFormat--}
```
public Measure.NumberFormatList getDistanceFormat()
```


用于测量任意方向距离的数字格式数组。

**退货：**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList 值
### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


应在默认用户空间坐标中指定测量坐标系原点的点。

**退货：**
[Point](../../com.aspose.pdf/point) 点对象
### getScaleRatio() {#getScaleRatio--}
```
public String getScaleRatio()
```


表示绘图比例的文本字符串。

**退货：**
java.lang.String - 字符串对象
### getSlopeFormat() {#getSlopeFormat--}
```
public Measure.NumberFormatList getSlopeFormat()
```


用于测量直线斜率的数字格式数组。

**退货：**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList 值
### getXFormat() {#getXFormat--}
```
public Measure.NumberFormatList getXFormat()
```


一个数字格式数组，用于测量沿 x 轴的变化，如果 Y 不存在，则也沿 y 轴

**退货：**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList 值
### getXYFactor() {#getXYFactor--}
```
public double getXYFactor()
```


一个系数，用于将沿 y 轴的最大单位转换为沿 x 轴的最大单位。

**退货：**
双倍价值
### getYFormat() {#getYFormat--}
```
public Measure.NumberFormatList getYFormat()
```


用于测量沿 y 轴变化的数字格式数组。

**退货：**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList 值
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




### setAngleFormat(Measure.NumberFormatList value) {#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setAngleFormat(Measure.NumberFormatList value)
```


用于测量角度的数字格式数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList 值 |

### setAreaFormat(Measure.NumberFormatList value) {#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setAreaFormat(Measure.NumberFormatList value)
```


用于面积测量的数字格式数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList 对象 |

### setDistanceFormat(Measure.NumberFormatList value) {#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setDistanceFormat(Measure.NumberFormatList value)
```


用于测量任意方向距离的数字格式数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList 值 |

### setOrigin(Point value) {#setOrigin-com.aspose.pdf.Point-}
```
public void setOrigin(Point value)
```


应在默认用户空间坐标中指定测量坐标系原点的点。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | 点对象 |

### setScaleRatio(String value) {#setScaleRatio-java.lang.String-}
```
public void setScaleRatio(String value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSlopeFormat(Measure.NumberFormatList value) {#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setSlopeFormat(Measure.NumberFormatList value)
```


用于测量直线斜率的数字格式数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList 值 |

### setXFormat(Measure.NumberFormatList value) {#setXFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setXFormat(Measure.NumberFormatList value)
```


一个数字格式数组，用于测量沿 x 轴的变化，如果 Y 不存在，则也沿 y 轴

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList 值 |

### setXYFactor(double value) {#setXYFactor-double-}
```
public void setXYFactor(double value)
```


一个系数，用于将沿 y 轴的最大单位转换为沿 x 轴的最大单位。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setYFormat(Measure.NumberFormatList value) {#setYFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setYFormat(Measure.NumberFormatList value)
```


用于测量沿 y 轴变化的数字格式数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList 值 |

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
