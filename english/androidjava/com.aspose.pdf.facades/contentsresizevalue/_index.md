---
title: IPdfFileEditor.ContentsResizeValue
second_title: Aspose.PDF for Java API Reference
description: Value of margin or content size specified in percents of default space units.
type: docs
weight: 11
url: /java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object
```
public static class IPdfFileEditor.ContentsResizeValue
```

Value of margin or content size specified in percents of default space units. This class is used in ContentsResizeParameters.
## Methods

| Method | Description |
| --- | --- |
| [setPercentValue(double value)](#setPercentValue-double-) | Sets value in percents of page size. |
| [setUnitValue(double value)](#setUnitValue-double-) | Sets value in default space units. |
| [getValue()](#getValue--) | Gets specified value. |
| [isPercent()](#isPercent--) | Gets true if value is expressed in percents; False if value is expressed in default units. |
| [percents(double value)](#percents-double-) | Initializes value in percents. |
| [units(double value)](#units-double-) | Initializes value in default space units. |
| [auto()](#auto--) | Initializes automatically calculated value. |
### setPercentValue(double value) {#setPercentValue-double-}
```
public void setPercentValue(double value)
```


Sets value in percents of page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setUnitValue(double value) {#setUnitValue-double-}
```
public void setUnitValue(double value)
```


Sets value in default space units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getValue() {#getValue--}
```
public double getValue()
```


Gets specified value. Use Unit property to get value units.

**Returns:**
double - double value
### isPercent() {#isPercent--}
```
public boolean isPercent()
```


Gets true if value is expressed in percents; False if value is expressed in default units.

**Returns:**
boolean - boolean value
### percents(double value) {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```


Initializes value in percents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value in percents. |

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - New value instance.
### units(double value) {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```


Initializes value in default space units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Value in percents. |

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - New value instance.
### auto() {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```


Initializes automatically calculated value.

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - New value instance.
