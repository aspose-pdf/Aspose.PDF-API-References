---
title: TextFragmentState
second_title: Aspose.PDF for Java API Reference
description: Represents a text state of a text fragment.
type: docs
weight: 298
url: /java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextState](../../com.aspose.pdf/textstate)
```
public final class TextFragmentState extends TextState
```

Represents a text state of a text fragment.

--------------------

> ```
> The example demonstrates how to change text color and font size of the text with ```
> TextState
> ``` object.
>    
>   // Open document
>   Document doc = new Document("D:\Tests\input.pdf");
>   
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.getPages(1).accept(absorber);
>   
>   // Change foreground color of the first text occurrence
>   absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED);
>   // Change font size of the first text occurrence
>   absorber.getTextFragments.get(1).getTextState().setFontSize ( 15);
>   
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

--------------------

Provides a way to change following properties of the text: font ( TextFragmentState.Font  property) font size ( TextFragmentState.FontSize  property) font style ( TextFragmentState.FontStyle  property) foreground color ( TextFragmentState.ForegroundColor  property) background color ( TextFragmentState.BackgroundColor  property) Note that changing  TextFragmentState  properties may change inner  TextFragment.Segments  collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the  TextFragment.Segments  collection unchanged, please change inner segments individually.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragmentState(TextFragment fragment)](#TextFragmentState-com.aspose.pdf.TextFragment-) | Initializes new instance of the  TextFragmentState  object with specified  TextFragment  object. |
## Methods

| Method | Description |
| --- | --- |
| [getCharacterSpacing()](#getCharacterSpacing--) | Gets character spacing of the text, represented by the  TextFragment  object. |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) |  |
| [getHorizontalScaling()](#getHorizontalScaling--) |  |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) |  |
| [getWordSpacing()](#getWordSpacing--) |  |
| [setWordSpacing(float value)](#setWordSpacing-float-) |  |
| [getLineSpacing()](#getLineSpacing--) | Gets or sets line spacing of the text. |
| [setLineSpacing(float value)](#setLineSpacing-float-) |  |
| [getForegroundColor()](#getForegroundColor--) | Gets foreground color of the text, represented by the  TextFragment  object |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.java.awt.Color-) | Sets foreground color of the text, represented by the  TextFragment  object |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.java.awt.Color-) | Sets background color of the text, represented by the  TextFragment  object |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Sets underline for the text, represented by the  TextFragment  object |
| [setFontStyle(int value)](#setFontStyle-int-) | Sets font style of the text, represented by the  TextFragment  object |
| [getFont()](#getFont--) | Gets font of the text, represented by the  TextFragment  object |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | Sets font of the text, represented by the  TextFragment  object |
| [getFontSize()](#getFontSize--) | Gets font size of the text, represented by the  TextFragment  object |
| [setFontSize(float value)](#setFontSize-float-) | Sets font size of the text, represented by the  TextFragment  object |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets or sets horizontal alignment for the text. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) |  |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | Applies settings from another textState |
| [applyChangesFrom(TextState textState, boolean groupChangesOnly)](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Applies settings from another textState |
### TextFragmentState(TextFragment fragment) {#TextFragmentState-com.aspose.pdf.TextFragment-}
```
public TextFragmentState(TextFragment fragment)
```


Initializes new instance of the  TextFragmentState  object with specified  TextFragment  object. This  TextFragmentState  initialization is not supported. TextFragmentState is only available with  TextFragment.TextState  property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fragment | [TextFragment](../../com.aspose.pdf/textfragment) |  |

### getCharacterSpacing() {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```


Gets character spacing of the text, represented by the  TextFragment  object.

**Returns:**
float - float value
### setCharacterSpacing(float value) {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```




**Returns:**
float
### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWordSpacing() {#getWordSpacing--}
```
public float getWordSpacing()
```




**Returns:**
float
### setWordSpacing(float value) {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLineSpacing() {#getLineSpacing--}
```
public float getLineSpacing()
```


Gets or sets line spacing of the text.

--------------------

Note that the value is not preserved as a text characteristic within the document. The LineSpacing property getter works for an object in case it was explicitly set previously with LineSpacing setter for those object. The property is used by runtime in context of current generation/modification process.

**Returns:**
float
### setLineSpacing(float value) {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gets foreground color of the text, represented by the  TextFragment  object

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.java.awt.Color-}
```
public void setForegroundColor(Color value)
```


Sets foreground color of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.java.awt.Color-}
```
public void setBackgroundColor(Color value)
```


Sets background color of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```


Sets underline for the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFontStyle(int value) {#setFontStyle-int-}
```
public void setFontStyle(int value)
```


Sets font style of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Gets font of the text, represented by the  TextFragment  object

**Returns:**
[Font](../../com.aspose.pdf/font)
### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```


Sets font of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) |  |

### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Gets font size of the text, represented by the  TextFragment  object

**Returns:**
float
### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


Sets font size of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets or sets horizontal alignment for the text.

--------------------

HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextFragmentState.VerticalAlignment property works in new document deneration generation scenarios only.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### applyChangesFrom(TextState textState) {#applyChangesFrom-com.aspose.pdf.TextState-}
```
public void applyChangesFrom(TextState textState)
```


Applies settings from another textState

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) |  |

### applyChangesFrom(TextState textState, boolean groupChangesOnly) {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
```
public void applyChangesFrom(TextState textState, boolean groupChangesOnly)
```


Applies settings from another textState

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) |  |
| groupChangesOnly | boolean | if true inherit group changes only (without isolating the segments into single segment) |

