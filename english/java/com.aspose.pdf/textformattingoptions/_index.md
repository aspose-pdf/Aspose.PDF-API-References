---
title: TextFormattingOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text formatting options
type: docs
weight: 5080
url: /java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Represents text formatting options

## Constructors

| Constructor | Description |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Initializes new instance of the {@code TextFormattingOptions} object with undefined word wrap mode. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Initializes new instance of the {@code TextFormattingOptions} object for the specified word wrap mode. |

## Methods

| Method | Description |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Gets or sets first line indent value. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Gets or sets hyphen symbol that is used in hyphenation process. </p><hr> To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | Gets line spacing mode. Default value is LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Gets or sets subsequent lines indent value. |
| [getWrapMode](#getWrapMode--) | Gets word wrap mode. Default value is WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Gets or sets first line indent value. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Gets or sets hyphen symbol that is used in hyphenation process. </p><hr> To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | Sets line spacing mode. Default value is LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Gets or sets subsequent lines indent value. |
| [setWrapMode](#setWrapMode-int-) | Sets word wrap mode. Default value is WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Initializes new instance of the {@code TextFormattingOptions} object with undefined word wrap mode.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Initializes new instance of the {@code TextFormattingOptions} object for the specified word wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wrapMode |  | Word wrap mode. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Gets or sets first line indent value.

**Returns:**
float value

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Gets or sets hyphen symbol that is used in hyphenation process. </p><hr> To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

**Returns:**
String value

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Gets line spacing mode. Default value is LineSpacingMode.FontSize

**Returns:**
int value @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Gets or sets subsequent lines indent value.

**Returns:**
float value

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Gets word wrap mode. Default value is WordWrapMode.NoWrap

**Returns:**
WordWrapMode value @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Gets or sets first line indent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Gets or sets hyphen symbol that is used in hyphenation process. </p><hr> To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Sets line spacing mode. Default value is LineSpacingMode.FontSize

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Gets or sets subsequent lines indent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Sets word wrap mode. Default value is WordWrapMode.NoWrap

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | WordWrapMode value @see WordWrapMode |
