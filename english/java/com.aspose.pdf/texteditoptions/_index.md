---
title: TextEditOptions
second_title: Aspose.PDF for Java API Reference
description: Descubes options of text edit operations.
type: docs
weight: 368
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
| [TextEditOptions(TextEditOptions.NoCharacterAction noCharacterBehavior)](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode. |
| [TextEditOptions(TextEditOptions.TextRearrangement option)](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Initializes new instance of the  TextEditOptions  object for the specified FontReplace behavior mode. |
| [TextEditOptions(TextEditOptions.FontReplace option)](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Initializes new instance of the  TextEditOptions  object for the specified FontReplace behavior mode. |
| [TextEditOptions(TextEditOptions.LanguageTransformation option)](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Initializes new instance of the  TextEditOptions  object for the specified LanguageTransformation behavior mode. |
| [TextEditOptions(boolean allowLanguageTransformation)](#TextEditOptions-boolean-) | Initializes new instance of the  TextEditOptions  object for the specified language transformation permission. |
## Methods

| Method | Description |
| --- | --- |
| [getReplacementFont()](#getReplacementFont--) | Gets or sets font used for replacing if user font does not contain required character |
| [setReplacementFont(Font value)](#setReplacementFont-com.aspose.pdf.Font-) | Gets or sets font used for replacing if user font does not contain required character |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [setNoCharacterBehavior(TextEditOptions.NoCharacterAction value)](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | Gets mode that defines behavior for fonts replacement scenarios. |
| [setFontReplaceBehavior(TextEditOptions.FontReplace value)](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Sets mode that defines behavior for fonts replacement scenarios. |
| [getAllowLanguageTransformation()](#getAllowLanguageTransformation--) | Gets value that permits usage of language transformation during adding or editing of text. |
| [setAllowLanguageTransformation(boolean value)](#setAllowLanguageTransformation-boolean-) | Sets value that permits usage of language transformation during adding or editing of text. |
| [getLanguageTransformationBehavior()](#getLanguageTransformationBehavior--) | Gets mode that defines behavior for language transformation scenarios. |
| [setLanguageTransformationBehavior(TextEditOptions.LanguageTransformation value)](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Sets mode that defines behavior for language transformation scenarios. |
| [getClippingPathsProcessing()](#getClippingPathsProcessing--) | Gets mode for processing clipping path of the edited text. |
| [setClippingPathsProcessing(TextEditOptions.ClippingPathsProcessingMode value)](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Gets mode for processing clipping path of the edited text. |
| [getToAttemptGetUnderlineFromSource()](#getToAttemptGetUnderlineFromSource--) | Gets or sets value that permits searching for text underlining on the page of source document. |
| [setToAttemptGetUnderlineFromSource(boolean value)](#setToAttemptGetUnderlineFromSource-boolean-) | Gets or sets value that permits searching for text underlining on the page of source document. |
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


Initializes new instance of the  TextEditOptions  object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions(TextEditOptions.NoCharacterAction noCharacterBehavior) {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
```
public TextEditOptions(TextEditOptions.NoCharacterAction noCharacterBehavior)
```


Initializes new instance of the  TextEditOptions  object for the specified no-character behavior mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| noCharacterBehavior | [NoCharacterAction](../../com.aspose.pdf/nocharacteraction) | No-character behavior mode object. |

### TextEditOptions(TextEditOptions.TextRearrangement option) {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
```
public TextEditOptions(TextEditOptions.TextRearrangement option)
```


Initializes new instance of the  TextEditOptions  object for the specified FontReplace behavior mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| option | com.aspose.pdf.TextEditOptions.TextRearrangement | value for FontReplace |

### TextEditOptions(TextEditOptions.FontReplace option) {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
```
public TextEditOptions(TextEditOptions.FontReplace option)
```


Initializes new instance of the  TextEditOptions  object for the specified FontReplace behavior mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| option | [FontReplace](../../com.aspose.pdf/fontreplace) | FontReplace |

### TextEditOptions(TextEditOptions.LanguageTransformation option) {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
```
public TextEditOptions(TextEditOptions.LanguageTransformation option)
```


Initializes new instance of the  TextEditOptions  object for the specified LanguageTransformation behavior mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| option | [LanguageTransformation](../../com.aspose.pdf/languagetransformation) | LanguageTransformation |

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
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```


Gets mode that defines behavior in case fonts don't contain requested characters.

**Returns:**
[NoCharacterAction](../../com.aspose.pdf/nocharacteraction) - NoCharacterAction value
### setNoCharacterBehavior(TextEditOptions.NoCharacterAction value) {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
```
public void setNoCharacterBehavior(TextEditOptions.NoCharacterAction value)
```


Sets mode that defines behavior in case fonts don't contain requested characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NoCharacterAction](../../com.aspose.pdf/nocharacteraction) | NoCharacterAction value |

### getFontReplaceBehavior() {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```


Gets mode that defines behavior for fonts replacement scenarios.

**Returns:**
[FontReplace](../../com.aspose.pdf/fontreplace) - FontReplace value
### setFontReplaceBehavior(TextEditOptions.FontReplace value) {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
```
public void setFontReplaceBehavior(TextEditOptions.FontReplace value)
```


Sets mode that defines behavior for fonts replacement scenarios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FontReplace](../../com.aspose.pdf/fontreplace) | FontReplace value |

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
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```


Gets mode that defines behavior for language transformation scenarios.

**Returns:**
[LanguageTransformation](../../com.aspose.pdf/languagetransformation) - LanguageTransformation value
### setLanguageTransformationBehavior(TextEditOptions.LanguageTransformation value) {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
```
public void setLanguageTransformationBehavior(TextEditOptions.LanguageTransformation value)
```


Sets mode that defines behavior for language transformation scenarios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LanguageTransformation](../../com.aspose.pdf/languagetransformation) | LanguageTransformation value |

### getClippingPathsProcessing() {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```


Gets mode for processing clipping path of the edited text.

**Returns:**
[ClippingPathsProcessingMode](../../com.aspose.pdf/clippingpathsprocessingmode) - ClippingPathsProcessingMode element
### setClippingPathsProcessing(TextEditOptions.ClippingPathsProcessingMode value) {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
```
public final void setClippingPathsProcessing(TextEditOptions.ClippingPathsProcessingMode value)
```


Gets mode for processing clipping path of the edited text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ClippingPathsProcessingMode](../../com.aspose.pdf/clippingpathsprocessingmode) | ClippingPathsProcessingMode element |

### getToAttemptGetUnderlineFromSource() {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```


Gets or sets value that permits searching for text underlining on the page of source document.

(Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this.

**Returns:**
boolean - boolean value
### setToAttemptGetUnderlineFromSource(boolean value) {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```


Gets or sets value that permits searching for text underlining on the page of source document.

(Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

