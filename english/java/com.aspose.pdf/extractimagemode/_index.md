---
title: ExtractImageMode
second_title: Aspose.PDF for Java API Reference
description: Defines different modes which can be used while extracting images from documents.
type: docs
weight: 1360
url: /java/com.aspose.pdf/extractimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ExtractImageMode > com.aspose.pdf.ExtractImageMode, java.lang.Enum < ExtractImageMode >, com.aspose.pdf.ExtractImageMode

**All Implemented Interfaces:**
Serializable, Comparable < ExtractImageMode >

```
public enum ExtractImageMode extends Enum < ExtractImageMode >
```

Defines different modes which can be used while extracting images from documents.

## Fields

| Field | Description |
| --- | --- |
| [ActuallyUsed](#ActuallyUsed) | Defines image extraction mode in which only those images are extracted that are actually shown on a page. |
| [DefinedInResources](#DefinedInResources) | Defines image extraction mode in which all images defined in resources for particular page are extracted. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### ActuallyUsed {#ActuallyUsed}
```
public static final ExtractImageMode ActuallyUsed
```

Defines image extraction mode in which only those images are extracted that are actually shown on a page.

### DefinedInResources {#DefinedInResources}
```
public static final ExtractImageMode DefinedInResources
```

Defines image extraction mode in which all images defined in resources for particular page are extracted.

### getByValue {#getByValue-int-}
```
public static ExtractImageMode getByValue(int value)
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
public static ExtractImageMode [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
