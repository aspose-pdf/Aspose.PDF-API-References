---
title: TextReplaceOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text replace options
type: docs
weight: 385
url: /java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextReplaceOptions extends TextOptions
```

Represents text replace options
## Constructors

| Constructor | Description |
| --- | --- |
| [TextReplaceOptions(TextReplaceOptions.Scope scope)](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Initializes new instance of the  TextReplaceOptions  object for the specified scope. |
| [TextReplaceOptions(TextReplaceOptions.ReplaceAdjustment adjustment)](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment-) | Initializes new instance of the  TextReplaceOptions  object for the specified after replace action. |
| [TextReplaceOptions(TextReplaceOptions.ReplaceAdjustment adjustment, TextReplaceOptions.Scope scope)](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment-com.aspose.pdf.TextReplaceOptions.Scope-) | Initializes new instance of the  TextReplaceOptions  object for the specified after replace action. |
| [TextReplaceOptions()](#TextReplaceOptions--) | Initializes new instance of the  TextReplaceOptions  object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE\_FIRST |
## Methods

| Method | Description |
| --- | --- |
| [getReplaceScope()](#getReplaceScope--) | Gets a scope where replace text operation is applied |
| [setReplaceScope(TextReplaceOptions.Scope value)](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Sets a scope where replace text operation is applied |
| [getReplaceAdjustmentAction()](#getReplaceAdjustmentAction--) | Gets an action that will be done after replace of text fragment to more short. |
| [setReplaceAdjustmentAction(TextReplaceOptions.ReplaceAdjustment value)](#setReplaceAdjustmentAction-com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment-) | Sets an action that will be done after replace of text fragment to more short. |
| [getAdjustmentNewLineSpacing()](#getAdjustmentNewLineSpacing--) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. |
| [setAdjustmentNewLineSpacing(double value)](#setAdjustmentNewLineSpacing-double-) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. |
### TextReplaceOptions(TextReplaceOptions.Scope scope) {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
```
public TextReplaceOptions(TextReplaceOptions.Scope scope)
```


Initializes new instance of the  TextReplaceOptions  object for the specified scope.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scope | [Scope](../../com.aspose.pdf/scope) | Scope object. |

### TextReplaceOptions(TextReplaceOptions.ReplaceAdjustment adjustment) {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment-}
```
public TextReplaceOptions(TextReplaceOptions.ReplaceAdjustment adjustment)
```


Initializes new instance of the  TextReplaceOptions  object for the specified after replace action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| adjustment | [ReplaceAdjustment](../../com.aspose.pdf/replaceadjustment) | ReplaceAdjustment object. |

### TextReplaceOptions(TextReplaceOptions.ReplaceAdjustment adjustment, TextReplaceOptions.Scope scope) {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment-com.aspose.pdf.TextReplaceOptions.Scope-}
```
public TextReplaceOptions(TextReplaceOptions.ReplaceAdjustment adjustment, TextReplaceOptions.Scope scope)
```


Initializes new instance of the  TextReplaceOptions  object for the specified after replace action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| adjustment | [ReplaceAdjustment](../../com.aspose.pdf/replaceadjustment) | ReplaceAdjustment object. |
| scope | [Scope](../../com.aspose.pdf/scope) | Scope object. |

### TextReplaceOptions() {#TextReplaceOptions--}
```
public TextReplaceOptions()
```


Initializes new instance of the  TextReplaceOptions  object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE\_FIRST

### getReplaceScope() {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```


Gets a scope where replace text operation is applied

**Returns:**
[Scope](../../com.aspose.pdf/scope) - int value
### setReplaceScope(TextReplaceOptions.Scope value) {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
```
public void setReplaceScope(TextReplaceOptions.Scope value)
```


Sets a scope where replace text operation is applied

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Scope](../../com.aspose.pdf/scope) | int value |

### getReplaceAdjustmentAction() {#getReplaceAdjustmentAction--}
```
public TextReplaceOptions.ReplaceAdjustment getReplaceAdjustmentAction()
```


Gets an action that will be done after replace of text fragment to more short.

**Returns:**
[ReplaceAdjustment](../../com.aspose.pdf/replaceadjustment) - ReplaceAdjustment element
### setReplaceAdjustmentAction(TextReplaceOptions.ReplaceAdjustment value) {#setReplaceAdjustmentAction-com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment-}
```
public void setReplaceAdjustmentAction(TextReplaceOptions.ReplaceAdjustment value)
```


Sets an action that will be done after replace of text fragment to more short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReplaceAdjustment](../../com.aspose.pdf/replaceadjustment) | ReplaceAdjustment element |

### getAdjustmentNewLineSpacing() {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```


Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2.

**Returns:**
double - double value
### setAdjustmentNewLineSpacing(double value) {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```


Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

