---
title: TextFormattingOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text formatting options
type: docs
weight: 373
url: /java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextFormattingOptions extends TextOptions
```

Represents text formatting options
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFormattingOptions(int wrapMode)](#TextFormattingOptions-int-) | Initializes new instance of the  TextFormattingOptions  object for the specified word wrap mode. |
| [TextFormattingOptions()](#TextFormattingOptions--) | Initializes new instance of the  TextFormattingOptions  object with undefined word wrap mode. |
## Methods

| Method | Description |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Gets word wrap mode. |
| [setWrapMode(int value)](#setWrapMode-int-) | Sets word wrap mode. |
| [getLineSpacing()](#getLineSpacing--) | Gets line spacing mode. |
| [setLineSpacing(int value)](#setLineSpacing-int-) | Sets line spacing mode. |
| [getHyphenSymbol()](#getHyphenSymbol--) | Gets or sets hyphen symbol that is used in hyphenation process. |
| [setHyphenSymbol(String value)](#setHyphenSymbol-java.lang.String-) | Gets or sets hyphen symbol that is used in hyphenation process. |
| [getSubsequentLinesIndent()](#getSubsequentLinesIndent--) | Gets or sets subsequent lines indent value. |
| [setSubsequentLinesIndent(float value)](#setSubsequentLinesIndent-float-) | Gets or sets subsequent lines indent value. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Gets or sets first line indent value. |
| [setFirstLineIndent(float value)](#setFirstLineIndent-float-) | Gets or sets first line indent value. |
### TextFormattingOptions(int wrapMode) {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```


Initializes new instance of the  TextFormattingOptions  object for the specified word wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wrapMode | int | Word wrap mode. |

### TextFormattingOptions() {#TextFormattingOptions--}
```
public TextFormattingOptions()
```


Initializes new instance of the  TextFormattingOptions  object with undefined word wrap mode.

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets word wrap mode. Default value is WordWrapMode.NoWrap

**Returns:**
int - WordWrapMode value
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Sets word wrap mode. Default value is WordWrapMode.NoWrap

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | WordWrapMode value |

### getLineSpacing() {#getLineSpacing--}
```
public int getLineSpacing()
```


Gets line spacing mode. Default value is LineSpacingMode.FontSize

**Returns:**
int - int value
### setLineSpacing(int value) {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```


Sets line spacing mode. Default value is LineSpacingMode.FontSize

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getHyphenSymbol() {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```


Gets or sets hyphen symbol that is used in hyphenation process.

--------------------

To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

**Returns:**
java.lang.String - String value
### setHyphenSymbol(String value) {#setHyphenSymbol-java.lang.String-}
```
public final void setHyphenSymbol(String value)
```


Gets or sets hyphen symbol that is used in hyphenation process.

--------------------

To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | value String value |

### getSubsequentLinesIndent() {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```


Gets or sets subsequent lines indent value.

**Returns:**
float - float value
### setSubsequentLinesIndent(float value) {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```


Gets or sets subsequent lines indent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getFirstLineIndent() {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```


Gets or sets first line indent value.

**Returns:**
float - float value
### setFirstLineIndent(float value) {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```


Gets or sets first line indent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

