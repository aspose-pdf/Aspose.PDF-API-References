---
title: TextReplaceOptions.FontSizeAdjustment
second_title: Aspose.PDF for Java API Reference
description: Specifies a policy for how the font size of text should be adjusted to fit within a containing area.
type: docs
weight: 5260
url: /java/com.aspose.pdf/textreplaceoptions.fontsizeadjustment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment > com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment >, com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.FontSizeAdjustment >

```
public static enum TextReplaceOptions.FontSizeAdjustment extends Enum < TextReplaceOptions.FontSizeAdjustment >
```

Specifies a policy for how the font size of text should be adjusted to fit within a containing area.

## Fields

| Field | Description |
| --- | --- |
| [None](#None) | The font size is not changed. |
| [ScaleToFill](#ScaleToFill) | The font size is adjusted (both shrinking and growing) to make the text fill the bounds of the rectangle as much as possible. |
| [ShrinkToFit](#ShrinkToFit) | The font size is reduced if the text is too large to fit the bounds. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### None {#None}
```
public static final TextReplaceOptions.FontSizeAdjustment None
```

The font size is not changed.

### ScaleToFill {#ScaleToFill}
```
public static final TextReplaceOptions.FontSizeAdjustment ScaleToFill
```

The font size is adjusted (both shrinking and growing) to make the text fill the bounds of the rectangle as much as possible.

### ShrinkToFit {#ShrinkToFit}
```
public static final TextReplaceOptions.FontSizeAdjustment ShrinkToFit
```

The font size is reduced if the text is too large to fit the bounds.

### getByValue {#getByValue-int-}
```
public static TextReplaceOptions.FontSizeAdjustment getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static TextReplaceOptions.FontSizeAdjustment [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
