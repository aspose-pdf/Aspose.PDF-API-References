---
title: HtmlDiffOutputGenerator
linktitle: HtmlDiffOutputGenerator
second_title: Aspose.PDF for Java API Reference
description: Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by - paragraph mark.
type: docs
weight: 10
url: /java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by - paragraph mark.

## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Creates an instance of {@link HtmlDiffOutputGenerator} class. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Creates an instance of {@link HtmlDiffOutputGenerator} class. |

## Methods

| Method | Description |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Generates the output based on the differences between texts and saves it to a file. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Generates the output based on the differences between texts and saves it to a file. |
| [generateOutput1](#generateOutput1-java.util.List-) | Generates the output based on the differences between texts and saves it to a file. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Generates the output based on the differences between texts and saves it to a file. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Internal method |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Gets and sets the CSS-style string for Delete operation. Example: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Gets and sets the CSS-style string for Equal operation. Example: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Gets and sets the CSS-style string for Insert operation. Example: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Get or set text-decoration: line-through style for the delete operation. Default value is {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Gets and sets the CSS-style string for Delete operation. Example: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Gets and sets the CSS-style string for Equal operation. Example: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Gets and sets the CSS-style string for Insert operation. Example: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Get or set text-decoration: line-through style for the delete operation. Default value is {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Creates an instance of {@link HtmlDiffOutputGenerator} class.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Creates an instance of {@link HtmlDiffOutputGenerator} class.

### generateOutput {#generateOutput-java.util.List-}
Generates the output based on the differences between texts and saves it to a file.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Generates the output based on the differences between texts and saves it to a file.

### generateOutput1 {#generateOutput1-java.util.List-}
Generates the output based on the differences between texts and saves it to a file.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Generates the output based on the differences between texts and saves it to a file.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Internal method

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Gets and sets the CSS-style string for Delete operation. Example: color: #003300; background-color: #ccff66;

**Returns:**
String value

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Gets and sets the CSS-style string for Equal operation. Example: color: #003300; background-color: #ccff66;

**Returns:**
String value

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Gets and sets the CSS-style string for Insert operation. Example: color: #003300; background-color: #ccff66;

**Returns:**
String value

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Get or set text-decoration: line-through style for the delete operation. Default value is {@code False}.

**Returns:**
boolean value

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Gets and sets the CSS-style string for Delete operation. Example: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Gets and sets the CSS-style string for Equal operation. Example: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Gets and sets the CSS-style string for Insert operation. Example: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Get or set text-decoration: line-through style for the delete operation. Default value is {@code False}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
