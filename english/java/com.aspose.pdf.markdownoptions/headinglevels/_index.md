---
title: HeadingLevels
second_title: Aspose.PDF for Java API Reference
description: Represents a class to work with header levels based on font size.
type: docs
weight: 20
url: /java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Represents a class to work with header levels based on font size.

## Constructors

| Constructor | Description |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Creates a new instance of the HeadingLevels class. |
| [HeadingLevels](#HeadingLevels-double-) | Creates a new instance of the HeadingLevels class. |

## Methods

| Method | Description |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Adds heading levels. |
| [estimateLevel](#estimateLevel-double-) | Estimates the possible header level. If fontSize is not found in the list of levels, the level closest to this font size value will be returned. If fontSize is outside the minimum and maximum header levels specified, the method will return false. |
| [findLevel](#findLevel-double-int:A-) | Finds level for corresponding font size. Looking for an exact match. |
| [getAllLevels](#getAllLevels--) | Gets all heading levels. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Creates a new instance of the HeadingLevels class.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Creates a new instance of the HeadingLevels class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold |  | The threshold value to compare font sizes. Within the threshold, the header levels are the same. The threshold default value is 0.01. |

### addLevels {#addLevels-java.lang.Iterable-}
Adds heading levels.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Estimates the possible header level. If fontSize is not found in the list of levels, the level closest to this font size value will be returned. If fontSize is outside the minimum and maximum header levels specified, the method will return false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize |  | The font size. |

**Returns:**
Heading level.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Finds level for corresponding font size. Looking for an exact match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize |  | The font size. |
| level |  | The corresponding heading level for given font size. |

**Returns:**
False If the fontSize is not within the specified range.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Gets all heading levels.

**Returns:**
IEnumerable of Double
