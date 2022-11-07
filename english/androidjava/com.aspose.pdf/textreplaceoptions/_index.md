---
title: TextReplaceOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text replace options
type: docs
weight: 305
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
| [TextReplaceOptions(int scope)](#TextReplaceOptions-int-) | Initializes new instance of the  TextReplaceOptions  object for the specified scope. |
| [TextReplaceOptions(int adjustment, int scope)](#TextReplaceOptions-int-int-) | Initializes new instance of the  TextReplaceOptions  object for the specified after replace action. |
| [TextReplaceOptions()](#TextReplaceOptions--) | Initializes new instance of the  TextReplaceOptions  object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE\_FIRST |
## Methods

| Method | Description |
| --- | --- |
| [getReplaceScope()](#getReplaceScope--) | Gets a scope where replace text operation is applied |
| [setReplaceScope(int value)](#setReplaceScope-int-) | Sets a scope where replace text operation is applied |
| [getReplaceAdjustmentAction()](#getReplaceAdjustmentAction--) | Gets an action that will be done after replace of text fragment to more short. |
| [setReplaceAdjustmentAction(int value)](#setReplaceAdjustmentAction-int-) | Sets an action that will be done after replace of text fragment to more short. |
| [getAdjustmentNewLineSpacing()](#getAdjustmentNewLineSpacing--) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. |
| [setAdjustmentNewLineSpacing(double value)](#setAdjustmentNewLineSpacing-double-) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. |
### TextReplaceOptions(int scope) {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int scope)
```


Initializes new instance of the  TextReplaceOptions  object for the specified scope.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scope | int | Scope object. |

### TextReplaceOptions(int adjustment, int scope) {#TextReplaceOptions-int-int-}
```
public TextReplaceOptions(int adjustment, int scope)
```


Initializes new instance of the  TextReplaceOptions  object for the specified after replace action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| adjustment | int | ReplaceAdjustment object. |
| scope | int | Scope object. |

### TextReplaceOptions() {#TextReplaceOptions--}
```
public TextReplaceOptions()
```


Initializes new instance of the  TextReplaceOptions  object for the default adjustment and scope : ReplaceAdjustment.None and Scope.REPLACE\_FIRST

### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


Gets a scope where replace text operation is applied

**Returns:**
int - int value
### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


Sets a scope where replace text operation is applied

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getReplaceAdjustmentAction() {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```


Gets an action that will be done after replace of text fragment to more short.

**Returns:**
int - ReplaceAdjustment element
### setReplaceAdjustmentAction(int value) {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```


Sets an action that will be done after replace of text fragment to more short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ReplaceAdjustment element |

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

