---
title: PageCoordinateType
second_title: Aspose.PDF for Java API Reference
description: Describes page coordinate type. MediaBox = 0 CropBox = 1
type: docs
weight: 3350
url: /java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

Describes page coordinate type. MediaBox = 0 CropBox = 1

## Fields

| Field | Description |
| --- | --- |
| [CropBox](#CropBox) | The CropBox defines the region to which the page contents are to be clipped. |
| [MediaBox](#MediaBox) | The MediaBox is used to specify the width and height of the page. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

The CropBox defines the region to which the page contents are to be clipped.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

The MediaBox is used to specify the width and height of the page.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static PageCoordinateType [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
