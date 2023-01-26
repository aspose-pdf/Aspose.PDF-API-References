---
title: TextEditOptions
second_title: Aspose.PDF for Java API Reference
description: Descubes options of text edit operations.
type: docs
weight: 370
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
| [getReplacementFont()](#getReplacementFont--) | Gets or sets font used for replacing if user font does not contain required character |
| [setReplacementFont(Font value)](#setReplacementFont-com.aspose.pdf.Font-) | Gets or sets font used for replacing if user font does not contain required character |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | Gets mode that defines behavior for fonts replacement scenarios. |
| [setFontReplaceBehavior(int value)](#setFontReplaceBehavior-int-) | Sets mode that defines behavior for fonts replacement scenarios. |
| [getAllowLanguageTransformation()](#getAllowLanguageTransformation--) | Gets value that permits usage of language transformation during adding or editing of text. |
| [setAllowLanguageTransformation(boolean value)](#setAllowLanguageTransformation-boolean-) | Sets value that permits usage of language transformation during adding or editing of text. |
| [getLanguageTransformationBehavior()](#getLanguageTransformationBehavior--) | Gets mode that defines behavior for language transformation scenarios. |
| [setLanguageTransformationBehavior(int value)](#setLanguageTransformationBehavior-int-) | Sets mode that defines behavior for language transformation scenarios. |
| [getClippingPathsProcessing()](#getClippingPathsProcessing--) | Gets mode for processing clipping path of the edited text. |
| [setClippingPathsProcessing(int value)](#setClippingPathsProcessing-int-) | Gets mode for processing clipping path of the edited text. |
| [getToAttemptGetUnderlineFromSource()](#getToAttemptGetUnderlineFromSource--) | Gets or sets value that permits searching for text underlining on the page of source document. |
| [setToAttemptGetUnderlineFromSource(boolean value)](#setToAttemptGetUnderlineFromSource-boolean-) | Gets or sets value that permits searching for text underlining on the page of source document. |
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

### getReplacementFont() {#getReplacementFont--}
```
public final Font getReplacementFont()
```


Gets or sets font used for replacing if user font does not contain required character

**Returns:**
[Font](../../com.aspose.pdf/font) - Font instance
### setReplacementFont(Font value) {#setReplacementFont-com.aspose.pdf.Font-}
```
public final void setReplacementFont(Font value)
```


Gets or sets font used for replacing if user font does not contain required character

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Font instance |

### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


Gets mode that defines behavior in case fonts don't contain requested characters.

**Returns:**
int - NoCharacterAction value
### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```


Sets mode that defines behavior in case fonts don't contain requested characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | NoCharacterAction value |

### getFontReplaceBehavior() {#getFontReplaceBehavior--}
```
public int getFontReplaceBehavior()
```


Gets mode that defines behavior for fonts replacement scenarios.

**Returns:**
int - FontReplace value
### setFontReplaceBehavior(int value) {#setFontReplaceBehavior-int-}
```
public void setFontReplaceBehavior(int value)
```


Sets mode that defines behavior for fonts replacement scenarios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FontReplace value |

### getAllowLanguageTransformation() {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```


Gets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied.

**Returns:**
boolean - boolean value
### setAllowLanguageTransformation(boolean value) {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```


Sets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLanguageTransformationBehavior() {#getLanguageTransformationBehavior--}
```
public int getLanguageTransformationBehavior()
```


Gets mode that defines behavior for language transformation scenarios.

**Returns:**
int - LanguageTransformation value
### setLanguageTransformationBehavior(int value) {#setLanguageTransformationBehavior-int-}
```
public void setLanguageTransformationBehavior(int value)
```


Sets mode that defines behavior for language transformation scenarios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LanguageTransformation value |

### getClippingPathsProcessing() {#getClippingPathsProcessing--}
```
public final int getClippingPathsProcessing()
```


Gets mode for processing clipping path of the edited text.

**Returns:**
int - ClippingPathsProcessingMode element
### setClippingPathsProcessing(int value) {#setClippingPathsProcessing-int-}
```
public final void setClippingPathsProcessing(int value)
```


Gets mode for processing clipping path of the edited text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ClippingPathsProcessingMode element |

### getToAttemptGetUnderlineFromSource() {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```


Gets or sets value that permits searching for text underlining on the page of source document. (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this.

**Returns:**
boolean - boolean value
### setToAttemptGetUnderlineFromSource(boolean value) {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```


Gets or sets value that permits searching for text underlining on the page of source document. (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

