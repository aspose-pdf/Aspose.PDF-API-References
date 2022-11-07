---
title: TextEditOptions
second_title: Aspose.PDF for Java API Reference
description: Descubes options of text edit operations.
type: docs
weight: 291
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
| [TextEditOptions(int noCharacterBehavior)](#TextEditOptions-int-) | Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode. |
| [TextEditOptions(boolean allowLanguageTransformation)](#TextEditOptions-boolean-) | Initializes new instance of the  TextEditOptions  object for the specified language transformation permission. |
## Methods

| Method | Description |
| --- | --- |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | Gets mode that defines behavior for fonts replacement scenarios. |
| [setFontReplaceBehavior(int value)](#setFontReplaceBehavior-int-) | Sets mode that defines behavior for fonts replacement scenarios. |
| [getAllowLanguageTransformation()](#getAllowLanguageTransformation--) | Gets value that permits usage of language transformation during adding or editing of text. |
| [setAllowLanguageTransformation(boolean value)](#setAllowLanguageTransformation-boolean-) | Sets value that permits usage of language transformation during adding or editing of text. |
| [getLanguageTransformationBehavior()](#getLanguageTransformationBehavior--) | Gets mode that defines behavior for language transformation scenarios. |
| [setLanguageTransformationBehavior(int value)](#setLanguageTransformationBehavior-int-) | Sets mode that defines behavior for language transformation scenarios. |
| [getToAttemptGetUnderlineFromSource()](#getToAttemptGetUnderlineFromSource--) | Gets or sets value that permits searching for text underlining on the page of source document. false - text underlining that may present in source document will be ignored (default value). true - searching for text underlining will be performed in the source document. |
| [setToAttemptGetUnderlineFromSource(boolean value)](#setToAttemptGetUnderlineFromSource-boolean-) | Gets or sets value that permits searching for text underlining on the page of source document. false - text underlining that may present in source document will be ignored (default value). true - searching for text underlining will be performed in the source document. |
### TextEditOptions(int noCharacterBehavior) {#TextEditOptions-int-}
```
public TextEditOptions(int noCharacterBehavior)
```


Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode. Please init fontReplaceBehavior by using setFontReplaceBehavior(int)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| noCharacterBehavior | int | No-character behavior mode object. |

### TextEditOptions(boolean allowLanguageTransformation) {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```


Initializes new instance of the  TextEditOptions  object for the specified language transformation permission.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allowLanguageTransformation | boolean | Allows language transformation if set to true. |

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

### getToAttemptGetUnderlineFromSource() {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```


Gets or sets value that permits searching for text underlining on the page of source document. false - text underlining that may present in source document will be ignored (default value). true - searching for text underlining will be performed in the source document. It may dramatically decrease performance of text editing operations. It also may effect on page graphical elements those look like underlining.

**Returns:**
boolean - boolean value
### setToAttemptGetUnderlineFromSource(boolean value) {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```


Gets or sets value that permits searching for text underlining on the page of source document. false - text underlining that may present in source document will be ignored (default value). true - searching for text underlining will be performed in the source document. It may dramatically decrease performance of text editing operations. It also may effect on page graphical elements those look like underlining.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

