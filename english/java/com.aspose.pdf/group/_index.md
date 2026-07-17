---
title: Group
linktitle: Group
second_title: Aspose.PDF for Java API Reference
description: A group attributes class specifying the attributes of the page’s page group for use in the transparent imaging model.
type: docs
weight: 1850
url: /java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

A group attributes class specifying the attributes of the page’s page group for use in the transparent imaging model.

## Constructors

| Constructor | Description |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | The constructor. |

## Methods

| Method | Description |
| --- | --- |
| [getColorSpace](#getColorSpace--) | Gets ColorSpace <p> |
| [isKnockout](#isKnockout--) | for Internal usage only If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group’s initial backdrop and overwrite ("knock out") any earlier overlapping objects. |
| [isTransparency](#isTransparency--) | for Internal usage only returns The group transparency flag. |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | The group color space. |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group’s initial backdrop and overwrite ("knock out") any earlier overlapping objects. |

### Group {#Group-com.aspose.pdf.Page-}
The constructor.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Gets ColorSpace <p>

**Returns:**
ColorSpace value. @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

for Internal usage only If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group’s initial backdrop and overwrite ("knock out") any earlier overlapping objects.

**Returns:**
ExtendedBoolean element @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

for Internal usage only returns The group transparency flag.

**Returns:**
boolean value

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
The group color space.

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group’s initial backdrop and overwrite ("knock out") any earlier overlapping objects.
