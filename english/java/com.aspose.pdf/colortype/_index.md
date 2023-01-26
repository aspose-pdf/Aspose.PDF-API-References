---
title: ColorType
second_title: Aspose.PDF for Java API Reference
description: Specifies color type of elements on page.
type: docs
weight: 67
url: /java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorType extends System.Enum
```

Specifies color type of elements on page.
## Fields

| Field | Description |
| --- | --- |
| [Rgb](#Rgb) | RGB color type. |
| [Grayscale](#Grayscale) | Grayscale color type. |
| [BlackAndWhite](#BlackAndWhite) | Black and white color type. |
| [Undefined](#Undefined) | Undefined color type value. |
## Methods

| Method | Description |
| --- | --- |
| [getName(int value)](#getName-int-) | Returns String name for the enum value. |
### Rgb {#Rgb}
```
public static final int Rgb
```


RGB color type.

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Grayscale color type.

### BlackAndWhite {#BlackAndWhite}
```
public static final int BlackAndWhite
```


Black and white color type.

### Undefined {#Undefined}
```
public static final int Undefined
```


Undefined color type value.

### getName(int value) {#getName-int-}
```
public static String getName(int value)
```


Returns String name for the enum value.

--------------------

Example:
 String s = ColorType.getName(ColorType.Grayscale); 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Enum value |

**Returns:**
java.lang.String - Value's name
