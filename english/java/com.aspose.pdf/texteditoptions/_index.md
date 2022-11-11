---
title: TextEditOptions
second_title: Aspose.PDF for Java API Reference
description: Descubes options of text edit operations.
type: docs
weight: 366
url: /java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextEditOptions extends TextOptions
```

Descubes options of text edit operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) | Initializes new instance of the  TextEditOptions  object with default options. |
| [TextEditOptions(int noCharacterBehavior)](#TextEditOptions-int-) | Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode. |
| [TextEditOptions(int option, Class type)](#TextEditOptions-int-java.lang.Class-) | Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode. |
| [TextEditOptions(boolean allowLanguageTransformation)](#TextEditOptions-boolean-) | Initializes new instance of the  TextEditOptions  object for the specified language transformation permission. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowLanguageTransformation()](#getAllowLanguageTransformation--) | Gets value that permits usage of language transformation during adding or editing of text. |
| [getClass()](#getClass--) |  |
| [getClippingPathsProcessing()](#getClippingPathsProcessing--) | Gets mode for processing clipping path of the edited text. |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | Gets mode that defines behavior for fonts replacement scenarios. |
| [getLanguageTransformationBehavior()](#getLanguageTransformationBehavior--) | Gets mode that defines behavior for language transformation scenarios. |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [getReplacementFont()](#getReplacementFont--) | Gets or sets font used for replacing if user font does not contain required character |
| [getToAttemptGetUnderlineFromSource()](#getToAttemptGetUnderlineFromSource--) | Gets or sets value that permits searching for text underlining on the page of source document. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowLanguageTransformation(boolean value)](#setAllowLanguageTransformation-boolean-) | Sets value that permits usage of language transformation during adding or editing of text. |
| [setClippingPathsProcessing(int value)](#setClippingPathsProcessing-int-) | Gets mode for processing clipping path of the edited text. |
| [setFontReplaceBehavior(int value)](#setFontReplaceBehavior-int-) | Sets mode that defines behavior for fonts replacement scenarios. |
| [setLanguageTransformationBehavior(int value)](#setLanguageTransformationBehavior-int-) | Sets mode that defines behavior for language transformation scenarios. |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [setReplacementFont(Font value)](#setReplacementFont-com.aspose.pdf.Font-) | Gets or sets font used for replacing if user font does not contain required character |
| [setToAttemptGetUnderlineFromSource(boolean value)](#setToAttemptGetUnderlineFromSource-boolean-) | Gets or sets value that permits searching for text underlining on the page of source document. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


Initializes new instance of the  TextEditOptions  object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions(int noCharacterBehavior) {#TextEditOptions-int-}
```
public TextEditOptions(int noCharacterBehavior)
```


Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode. Please init fontReplaceBehavior by using setFontReplaceBehavior(int)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| noCharacterBehavior | int | No-character behavior mode object. |

### TextEditOptions(int option, Class type) {#TextEditOptions-int-java.lang.Class-}
```
public TextEditOptions(int option, Class type)
```


Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode. Please init fontReplaceBehavior by using setFontReplaceBehavior(int)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| option | int | value for one from the following classes: NoCharacterAction, LanguageTransformation, FontReplace, |
| type | java.lang.Class | class of the option |

### TextEditOptions(boolean allowLanguageTransformation) {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```


Initializes new instance of the  TextEditOptions  object for the specified language transformation permission.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allowLanguageTransformation | boolean | Allows language transformation if set to true. |

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
### getAllowLanguageTransformation() {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```


Gets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied.

**Returns:**
boolean - boolean value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPathsProcessing() {#getClippingPathsProcessing--}
```
public final int getClippingPathsProcessing()
```


Gets mode for processing clipping path of the edited text.

**Returns:**
int - ClippingPathsProcessingMode element
### getFontReplaceBehavior() {#getFontReplaceBehavior--}
```
public int getFontReplaceBehavior()
```


Gets mode that defines behavior for fonts replacement scenarios.

**Returns:**
int - FontReplace value
### getLanguageTransformationBehavior() {#getLanguageTransformationBehavior--}
```
public int getLanguageTransformationBehavior()
```


Gets mode that defines behavior for language transformation scenarios.

**Returns:**
int - LanguageTransformation value
### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


Gets mode that defines behavior in case fonts don't contain requested characters.

**Returns:**
int - NoCharacterAction value
### getReplacementFont() {#getReplacementFont--}
```
public final Font getReplacementFont()
```


Gets or sets font used for replacing if user font does not contain required character

**Returns:**
[Font](../../com.aspose.pdf/font) - Font instance
### getToAttemptGetUnderlineFromSource() {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```


Gets or sets value that permits searching for text underlining on the page of source document. (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this.

**Returns:**
boolean - boolean value
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




### setAllowLanguageTransformation(boolean value) {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```


Sets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setClippingPathsProcessing(int value) {#setClippingPathsProcessing-int-}
```
public final void setClippingPathsProcessing(int value)
```


Gets mode for processing clipping path of the edited text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ClippingPathsProcessingMode element |

### setFontReplaceBehavior(int value) {#setFontReplaceBehavior-int-}
```
public void setFontReplaceBehavior(int value)
```


Sets mode that defines behavior for fonts replacement scenarios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FontReplace value |

### setLanguageTransformationBehavior(int value) {#setLanguageTransformationBehavior-int-}
```
public void setLanguageTransformationBehavior(int value)
```


Sets mode that defines behavior for language transformation scenarios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LanguageTransformation value |

### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```


Sets mode that defines behavior in case fonts don't contain requested characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | NoCharacterAction value |

### setReplacementFont(Font value) {#setReplacementFont-com.aspose.pdf.Font-}
```
public final void setReplacementFont(Font value)
```


Gets or sets font used for replacing if user font does not contain required character

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Font instance |

### setToAttemptGetUnderlineFromSource(boolean value) {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```


Gets or sets value that permits searching for text underlining on the page of source document. (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

