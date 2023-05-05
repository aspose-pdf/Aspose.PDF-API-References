---
title: HorizontalAlignment
second_title: Aspose.PDF for Java API Reference
description: Describes horizontal alignment.
type: docs
weight: 445
url: /java/com.aspose.pdf/horizontalalignment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HorizontalAlignment extends Enum<HorizontalAlignment>
```

Describes horizontal alignment.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No alignment. |
| [Left](#Left) | Align to left. |
| [Center](#Center) | Center alignment. |
| [Right](#Right) | Align to right. |
| [Justify](#Justify) | Justify alignment. |
| [FullJustify](#FullJustify) | Similar to 'Justify' alignment, except that the very last line will only be left-aligned in 'Justify' mode, while in 'FullJustify' mode all lines will be left- and right-aligned. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [valueOf(int alignmentType)](#valueOf-int-) |  |
| [getValue()](#getValue--) | Get number of |
### None {#None}
```
public static final HorizontalAlignment None
```


No alignment.

### Left {#Left}
```
public static final HorizontalAlignment Left
```


Align to left.

### Center {#Center}
```
public static final HorizontalAlignment Center
```


Center alignment.

### Right {#Right}
```
public static final HorizontalAlignment Right
```


Align to right.

### Justify {#Justify}
```
public static final HorizontalAlignment Justify
```


Justify alignment. Text will be aligned on both left and right margins.

### FullJustify {#FullJustify}
```
public static final HorizontalAlignment FullJustify
```


Similar to 'Justify' alignment, except that the very last line will only be left-aligned in 'Justify' mode, while in 'FullJustify' mode all lines will be left- and right-aligned.

### values() {#values--}
```
public static HorizontalAlignment[] values()
```




**Returns:**
com.aspose.pdf.HorizontalAlignment[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static HorizontalAlignment valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment)
### valueOf(int alignmentType) {#valueOf-int-}
```
public static HorizontalAlignment valueOf(int alignmentType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | int |  |

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment)
### getValue() {#getValue--}
```
public int getValue()
```


Get number of

**Returns:**
int - int value of the HorizontalAlignment element
