---
title: SideBySideComparisonOptions
linktitle: SideBySideComparisonOptions
second_title: Aspose.PDF for Java API Reference
description: Represents an options class for comparing documents with side-by-side output.
type: docs
weight: 60
url: /java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Represents an options class for comparing documents with side-by-side output.

## Constructors

| Constructor | Description |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Creates an instance of {@link SideBySideComparisonOptions} class. |

## Methods

| Method | Description |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options. |
| [getComparisonArea2](#getComparisonArea2--) | Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options. |
| [getComparisonMode](#getComparisonMode--) | Gets and sets a comparison mode. The default value is {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Gets the color used to mark deleted content during a side-by-side comparison. This property defines the visual representation for deletions in the comparison result. |
| [getExcludeAreas1](#getExcludeAreas1--) | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) option. |
| [getExcludeAreas2](#getExcludeAreas2--) | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) option. |
| [getExcludeTables](#getExcludeTables--) | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) and {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). The default value is {@code false}. |
| [getInsertColor](#getInsertColor--) | Gets the color used to mark inserted content during a side-by-side comparison. This property defines the visual representation for insertion in the comparison result. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options. |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options. |
| [setComparisonMode](#setComparisonMode-int-) | Gets and sets a comparison mode. The default value is {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Sets the color used to mark deleted content during a side-by-side comparison. This property defines the visual representation for deletions in the comparison result. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) option. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) option. |
| [setExcludeTables](#setExcludeTables-boolean-) | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) and {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). The default value is {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Sets the color used to mark inserted content during a side-by-side comparison. This property defines the visual representation for insertion in the comparison result. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Creates an instance of {@link SideBySideComparisonOptions} class.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is {@code false}.

**Returns:**
boolean value

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options.

**Returns:**
Rectangle instance

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options.

**Returns:**
Rectangle instance

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Gets and sets a comparison mode. The default value is {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
ComparisonMode element

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Gets the color used to mark deleted content during a side-by-side comparison. This property defines the visual representation for deletions in the comparison result.

**Returns:**
the color used to mark deleted content during a side-by-side comparison.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) option.

**Returns:**
array of Rectangle instances

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) option.

**Returns:**
array of Rectangle instances

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) and {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). The default value is {@code false}.

**Returns:**
boolean value

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Gets the color used to mark inserted content during a side-by-side comparison. This property defines the visual representation for insertion in the comparison result.

**Returns:**
the color used to mark inserted content during a side-by-side comparison.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options.

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) and {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) options.

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Gets and sets a comparison mode. The default value is {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ComparisonMode element |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Sets the color used to mark deleted content during a side-by-side comparison. This property defines the visual representation for deletions in the comparison result.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) option.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) option.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) and {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). The default value is {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Sets the color used to mark inserted content during a side-by-side comparison. This property defines the visual representation for insertion in the comparison result.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
