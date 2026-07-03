---
title: ComparisonOptions
second_title: Aspose.PDF for Java API Reference
description: Represents a PDF document comparison options class.
type: docs
weight: 10
url: /java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Represents a PDF document comparison options class.

## Constructors

| Constructor | Description |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Creates a {@link ComparisonOptions} class instance. |

## Methods

| Method | Description |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Gets and sets the edit operations order. |
| [getExcludeAreas1](#getExcludeAreas1--) | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [getExcludeAreas2](#getExcludeAreas2--) | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [getExtractionArea](#getExtractionArea--) | Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) and { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options. |
| [isExcludeTables](#isExcludeTables--) | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. The default value is {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Gets and sets the edit operations order. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [setExcludeTables](#setExcludeTables-boolean-) | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. The default value is {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) and { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Creates a {@link ComparisonOptions} class instance.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Gets and sets the edit operations order.

**Returns:**
EditOperationsOrder element

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

**Returns:**
array of Rectangle instances

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

**Returns:**
array of Rectangle instances

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) and { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options.

**Returns:**
Rectangle instance

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. The default value is {@code false}.

**Returns:**
boolean value

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Gets and sets the edit operations order.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). This option can't be setted along with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. The default value is {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) and { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options.
