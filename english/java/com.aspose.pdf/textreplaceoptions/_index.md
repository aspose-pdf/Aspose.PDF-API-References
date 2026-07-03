---
title: TextReplaceOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text replace options
type: docs
weight: 5250
url: /java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Represents text replace options

## Constructors

| Constructor | Description |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Initializes new instance of the {@code TextReplaceOptions} object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Initializes new instance of the {@code TextReplaceOptions} object for the specified after replace action. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Initializes new instance of the {@code TextReplaceOptions} object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Initializes new instance of the {@code TextReplaceOptions} object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE_FIRST |

## Methods

| Method | Description |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Gets or sets the policy for adjusting the font size to fit within the bounds defined by the {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | Gets left position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Gets or sets the rectangle to fit the text after replacement. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Gets an action that will be done after replace of text fragment to more short. |
| [getReplaceScope](#getReplaceScope--) | Gets a scope where replace text operation is applied |
| [getRightAdjustment](#getRightAdjustment--) | Sets or gets right position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Gets or sets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Gets or sets the policy for adjusting the font size to fit within the bounds defined by the TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Gets or sets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Sets or gets left position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Gets or sets the rectangle to fit the text after replacement. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Sets an action that will be done after replace of text fragment to more short. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Sets a scope where replace text operation is applied |
| [setRightAdjustment](#setRightAdjustment-double-) | Sets right position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Initializes new instance of the {@code TextReplaceOptions} object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Initializes new instance of the {@code TextReplaceOptions} object for the specified after replace action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| adjustment |  | ReplaceAdjustment object. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Initializes new instance of the {@code TextReplaceOptions} object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Initializes new instance of the {@code TextReplaceOptions} object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2.

**Returns:**
double value

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Gets or sets the policy for adjusting the font size to fit within the bounds defined by the {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
FontSizeAdjustment element

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Gets left position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double value

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Gets or sets the rectangle to fit the text after replacement.

**Returns:**
Rectangle instance

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Gets an action that will be done after replace of text fragment to more short.

**Returns:**
ReplaceAdjustment element @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Gets a scope where replace text operation is applied

**Returns:**
int value @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Sets or gets right position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double value

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Gets or sets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement.

**Returns:**
boolean velue

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Gets or sets the policy for adjusting the font size to fit within the bounds defined by the TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Gets or sets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Sets or gets left position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Gets or sets the rectangle to fit the text after replacement.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Sets an action that will be done after replace of text fragment to more short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ReplaceAdjustment element @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Sets a scope where replace text operation is applied

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

Sets right position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |
