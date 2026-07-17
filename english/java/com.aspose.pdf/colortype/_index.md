---
title: ColorType
linktitle: ColorType
second_title: Aspose.PDF for Java API Reference
description: Specifies color type of elements on page.
type: docs
weight: 710
url: /java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Specifies color type of elements on page.

## Fields

| Field | Description |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Black and white color type. |
| [Grayscale](#Grayscale) | Grayscale color type. |
| [Rgb](#Rgb) | RGB color type. |
| [Undefined](#Undefined) | Undefined color type value. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Returns String name for the enum value. </p> <hr> Example: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Black and white color type.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Grayscale color type.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

RGB color type.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Undefined color type value.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Returns String name for the enum value. </p> <hr> Example: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | Enum value |

**Returns:**
Value's name

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static ColorType [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
