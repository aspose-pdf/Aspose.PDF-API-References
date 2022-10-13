---
title: TextExtractionOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text extraction options
type: docs
weight: 293
url: /java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextExtractionOptions extends TextOptions
```

Represents text extraction options
## Constructors

| Constructor | Description |
| --- | --- |
| [TextExtractionOptions(int formattingMode)](#TextExtractionOptions-int-) | Initializes new instance of the  TextExtractionOptions  object for the specified text formatting mode. |
## Methods

| Method | Description |
| --- | --- |
| [getFormattingMode()](#getFormattingMode--) | Gets formatting mode. |
| [setFormattingMode(int value)](#setFormattingMode-int-) | Sets formatting mode. |
| [getScaleFactor()](#getScaleFactor--) | Gets factor that will be applied to scale font size during extraction in pure mode. |
| [setScaleFactor(double value)](#setScaleFactor-double-) | Sets factor that will be applied to scale font size during extraction in pure mode. |
### TextExtractionOptions(int formattingMode) {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```


Initializes new instance of the  TextExtractionOptions  object for the specified text formatting mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattingMode | int | Text formatting mode value. |

### getFormattingMode() {#getFormattingMode--}
```
public int getFormattingMode()
```


Gets formatting mode.

**Returns:**
int - TextFormattingMode value
### setFormattingMode(int value) {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```


Sets formatting mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TextFormattingMode value |

### getScaleFactor() {#getScaleFactor--}
```
public double getScaleFactor()
```


Gets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text. Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically.

**Returns:**
double - double value
### setScaleFactor(double value) {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```


Sets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text. Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

