---
title: TextReplaceOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text replace options
type: docs
weight: 384
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdjustmentNewLineSpacing()](#getAdjustmentNewLineSpacing--) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. |
| [getClass()](#getClass--) |  |
| [getReplaceAdjustmentAction()](#getReplaceAdjustmentAction--) | Gets an action that will be done after replace of text fragment to more short. |
| [getReplaceScope()](#getReplaceScope--) | Gets a scope where replace text operation is applied |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdjustmentNewLineSpacing(double value)](#setAdjustmentNewLineSpacing-double-) | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. |
| [setReplaceAdjustmentAction(int value)](#setReplaceAdjustmentAction-int-) | Sets an action that will be done after replace of text fragment to more short. |
| [setReplaceScope(int value)](#setReplaceScope-int-) | Sets a scope where replace text operation is applied |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdjustmentNewLineSpacing() {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```


Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2.

**Returns:**
double - double value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getReplaceAdjustmentAction() {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```


Gets an action that will be done after replace of text fragment to more short.

**Returns:**
int - ReplaceAdjustment element
### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


Gets a scope where replace text operation is applied

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdjustmentNewLineSpacing(double value) {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```


Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setReplaceAdjustmentAction(int value) {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```


Sets an action that will be done after replace of text fragment to more short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ReplaceAdjustment element |

### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


Sets a scope where replace text operation is applied

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

