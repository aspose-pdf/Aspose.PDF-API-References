---
title: ParagraphPositioningMode
second_title: Aspose.PDF for Java API Reference
description: Specifies variant for determining the location of the element on the page.
type: docs
weight: 3490
url: /java/com.aspose.pdf/paragraphpositioningmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ParagraphPositioningMode > com.aspose.pdf.ParagraphPositioningMode, java.lang.Enum < ParagraphPositioningMode >, com.aspose.pdf.ParagraphPositioningMode

**All Implemented Interfaces:**
Serializable, Comparable < ParagraphPositioningMode >

```
public enum ParagraphPositioningMode extends Enum < ParagraphPositioningMode >
```

Specifies variant for determining the location of the element on the page.

## Fields

| Field | Description |
| --- | --- |
| [Absolute](#Absolute) | The location is specified by the Left and Top values, does not depend on previous elements and does not affect the location of subsequent ones. |
| [Default](#Default) | The location is determined by the previously placed elements. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### Absolute {#Absolute}
```
public static final ParagraphPositioningMode Absolute
```

The location is specified by the Left and Top values, does not depend on previous elements and does not affect the location of subsequent ones.

### Default {#Default}
```
public static final ParagraphPositioningMode Default
```

The location is determined by the previously placed elements.

### getByValue {#getByValue-int-}
```
public static ParagraphPositioningMode getByValue(int value)
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
public static ParagraphPositioningMode [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
