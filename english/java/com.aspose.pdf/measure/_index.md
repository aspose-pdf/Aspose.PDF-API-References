---
title: Measure
second_title: Aspose.PDF for Java API Reference
description: Class which describes Measure coordinate system.
type: docs
weight: 210
url: /java/com.aspose.pdf/measure/
---
**Inheritance:**
java.lang.Object
```
public class Measure
```

Class which describes Measure coordinate system.
## Constructors

| Constructor | Description |
| --- | --- |
| [Measure(Annotation annotation)](#Measure-com.aspose.pdf.Annotation-) | Creates Measure object for measure annotations. |
## Methods

| Method | Description |
| --- | --- |
| [getScaleRatio()](#getScaleRatio--) | A text string expressing the scale ratio of the drawing. |
| [setScaleRatio(String value)](#setScaleRatio-java.lang.String-) |  |
| [getXFormat()](#getXFormat--) | A number format array for measurement of change along the xaxis and, if Y is not present, along the y axis as well |
| [setXFormat(Measure.NumberFormatList value)](#setXFormat-com.aspose.pdf.Measure.NumberFormatList-) | A number format array for measurement of change along the xaxis and, if Y is not present, along the y axis as well |
| [getYFormat()](#getYFormat--) | A number format array for measurement of change along the y axis. |
| [setYFormat(Measure.NumberFormatList value)](#setYFormat-com.aspose.pdf.Measure.NumberFormatList-) | A number format array for measurement of change along the y axis. |
| [getDistanceFormat()](#getDistanceFormat--) | A number format array for measurement of distance in any direction. |
| [setDistanceFormat(Measure.NumberFormatList value)](#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-) | A number format array for measurement of distance in any direction. |
| [getAreaFormat()](#getAreaFormat--) | A number format array for measurement of area. |
| [setAreaFormat(Measure.NumberFormatList value)](#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-) | A number format array for measurement of area. |
| [getAngleFormat()](#getAngleFormat--) | A number format array for measurement of angles. |
| [setAngleFormat(Measure.NumberFormatList value)](#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-) | A number format array for measurement of angles. |
| [getSlopeFormat()](#getSlopeFormat--) | A number format array for measurement of the slope of a line. |
| [setSlopeFormat(Measure.NumberFormatList value)](#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-) | A number format array for measurement of the slope of a line. |
| [getOrigin()](#getOrigin--) | Point that shall specify the origin of the measurement coordinate system in default user space coordinates. |
| [setOrigin(Point value)](#setOrigin-com.aspose.pdf.Point-) | Point that shall specify the origin of the measurement coordinate system in default user space coordinates. |
| [getXYFactor()](#getXYFactor--) | A factor that shall be used to convert the largest units along the y axis to the largest units along the x axis. |
| [setXYFactor(double value)](#setXYFactor-double-) | A factor that shall be used to convert the largest units along the y axis to the largest units along the x axis. |
### Measure(Annotation annotation) {#Measure-com.aspose.pdf.Annotation-}
```
public Measure(Annotation annotation)
```


Creates Measure object for measure annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation for which measure will be bound. |

### getScaleRatio() {#getScaleRatio--}
```
public String getScaleRatio()
```


A text string expressing the scale ratio of the drawing.

**Returns:**
java.lang.String - string object
### setScaleRatio(String value) {#setScaleRatio-java.lang.String-}
```
public void setScaleRatio(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXFormat() {#getXFormat--}
```
public Measure.NumberFormatList getXFormat()
```


A number format array for measurement of change along the xaxis and, if Y is not present, along the y axis as well

**Returns:**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList value
### setXFormat(Measure.NumberFormatList value) {#setXFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setXFormat(Measure.NumberFormatList value)
```


A number format array for measurement of change along the xaxis and, if Y is not present, along the y axis as well

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList value |

### getYFormat() {#getYFormat--}
```
public Measure.NumberFormatList getYFormat()
```


A number format array for measurement of change along the y axis.

**Returns:**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList value
### setYFormat(Measure.NumberFormatList value) {#setYFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setYFormat(Measure.NumberFormatList value)
```


A number format array for measurement of change along the y axis.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList value |

### getDistanceFormat() {#getDistanceFormat--}
```
public Measure.NumberFormatList getDistanceFormat()
```


A number format array for measurement of distance in any direction.

**Returns:**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList value
### setDistanceFormat(Measure.NumberFormatList value) {#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setDistanceFormat(Measure.NumberFormatList value)
```


A number format array for measurement of distance in any direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList value |

### getAreaFormat() {#getAreaFormat--}
```
public Measure.NumberFormatList getAreaFormat()
```


A number format array for measurement of area.

**Returns:**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList value
### setAreaFormat(Measure.NumberFormatList value) {#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setAreaFormat(Measure.NumberFormatList value)
```


A number format array for measurement of area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList object |

### getAngleFormat() {#getAngleFormat--}
```
public Measure.NumberFormatList getAngleFormat()
```


A number format array for measurement of angles.

**Returns:**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList value
### setAngleFormat(Measure.NumberFormatList value) {#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setAngleFormat(Measure.NumberFormatList value)
```


A number format array for measurement of angles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList value |

### getSlopeFormat() {#getSlopeFormat--}
```
public Measure.NumberFormatList getSlopeFormat()
```


A number format array for measurement of the slope of a line.

**Returns:**
[NumberFormatList](../../com.aspose.pdf/numberformatlist) - NumberFormatList value
### setSlopeFormat(Measure.NumberFormatList value) {#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-}
```
public void setSlopeFormat(Measure.NumberFormatList value)
```


A number format array for measurement of the slope of a line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NumberFormatList](../../com.aspose.pdf/numberformatlist) | NumberFormatList value |

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


Point that shall specify the origin of the measurement coordinate system in default user space coordinates.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point object
### setOrigin(Point value) {#setOrigin-com.aspose.pdf.Point-}
```
public void setOrigin(Point value)
```


Point that shall specify the origin of the measurement coordinate system in default user space coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | Point object |

### getXYFactor() {#getXYFactor--}
```
public double getXYFactor()
```


A factor that shall be used to convert the largest units along the y axis to the largest units along the x axis.

**Returns:**
double - double value
### setXYFactor(double value) {#setXYFactor-double-}
```
public void setXYFactor(double value)
```


A factor that shall be used to convert the largest units along the y axis to the largest units along the x axis.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

