---
title: TextExtractionOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text extraction options
type: docs
weight: 5060
url: /java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Represents text extraction options

## Constructors

| Constructor | Description |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Initializes new instance of the {@code TextExtractionOptions} object for the specified text formatting mode. |

## Methods

| Method | Description |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Gets formatting mode. |
| [getScaleFactor](#getScaleFactor--) | Gets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text. Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically. |
| [setFormattingMode](#setFormattingMode-int-) | Sets formatting mode. |
| [setScaleFactor](#setScaleFactor-double-) | Sets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text (from 1 to 10). Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Initializes new instance of the {@code TextExtractionOptions} object for the specified text formatting mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattingMode |  | Text formatting mode value. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Gets formatting mode.

**Returns:**
TextFormattingMode value @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Gets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text. Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically.

**Returns:**
double value

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Sets formatting mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | TextFormattingMode value @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Sets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text (from 1 to 10). Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |
