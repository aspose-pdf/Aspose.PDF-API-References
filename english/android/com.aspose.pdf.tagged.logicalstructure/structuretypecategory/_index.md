---
title: StructureTypeCategory
second_title: Aspose.PDF for Java API Reference
description: Represents Categories of Standard Structure Types.
type: docs
weight: 18
url: /java/com.aspose.pdf.tagged.logicalstructure/structuretypecategory/
---
**Inheritance:**
java.lang.Object
```
public final class StructureTypeCategory
```

Represents Categories of Standard Structure Types.
## Fields

| Field | Description |
| --- | --- |
| [GroupingElements](#GroupingElements) | Grouping elements group other elements into sequences or hierarchies but hold no content directly and have no direct effect on layout. |
| [BLSEs](#BLSEs) | Block-level structure elements (BLSEs) describe the overall layout of content on the page, proceeding in the block-progression direction. |
| [ILSEs](#ILSEs) | Inline-level structure elements (ILSEs) describe the layout of content within a BLSE, proceeding in the inline-progression direction. |
| [IllustrationElements](#IllustrationElements) | Illustration elements are compact sequences of content, in page content order, that are considered to be unitary objects with respect to page layout. |
## Methods

| Method | Description |
| --- | --- |
| [to_StructureTypeCategory(String name)](#to-StructureTypeCategory-java.lang.String-) | Performs an explicit conversion from String to [StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory). |
| [toString()](#toString--) | Returns a string that represents the current object. |
### GroupingElements {#GroupingElements}
```
public static final StructureTypeCategory GroupingElements
```


Grouping elements group other elements into sequences or hierarchies but hold no content directly and have no direct effect on layout.

### BLSEs {#BLSEs}
```
public static final StructureTypeCategory BLSEs
```


Block-level structure elements (BLSEs) describe the overall layout of content on the page, proceeding in the block-progression direction.

### ILSEs {#ILSEs}
```
public static final StructureTypeCategory ILSEs
```


Inline-level structure elements (ILSEs) describe the layout of content within a BLSE, proceeding in the inline-progression direction.

### IllustrationElements {#IllustrationElements}
```
public static final StructureTypeCategory IllustrationElements
```


Illustration elements are compact sequences of content, in page content order, that are considered to be unitary objects with respect to page layout. An illustration can be treated as either a BLSE or an ILSE.

### to_StructureTypeCategory(String name) {#to-StructureTypeCategory-java.lang.String-}
```
public static StructureTypeCategory to_StructureTypeCategory(String name)
```


Performs an explicit conversion from String to [StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name. |

**Returns:**
[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory) - The result of the conversion.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - String that represents the current object.
