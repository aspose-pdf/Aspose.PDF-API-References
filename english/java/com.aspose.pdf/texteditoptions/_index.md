---
title: TextEditOptions
linktitle: TextEditOptions
second_title: Aspose.PDF for Java API Reference
description: Descubes options of text edit operations.
type: docs
weight: 4970
url: /java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Descubes options of text edit operations.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Initializes new instance of the {@code TextEditOptions} object for the specified text rearrangement mode. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Methods

| Method | Description |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Gets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Gets mode for processing clipping path of the edited text. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Gets mode that defines behavior for fonts replacement scenarios. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Gets mode that defines behavior for language transformation scenarios. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [getReplacementFont](#getReplacementFont--) | Gets or sets font used for replacing if user font does not contain required character |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Gets or sets value that permits searching for text underlining on the page of source document. <p> (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Sets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Gets mode for processing clipping path of the edited text. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Sets mode that defines behavior for fonts replacement scenarios. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Sets mode that defines behavior for language transformation scenarios. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Gets or sets font used for replacing if user font does not contain required character |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Gets or sets value that permits searching for text underlining on the page of source document. <p> (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Initializes new instance of the {@code TextEditOptions} object for the specified text rearrangement mode. / * / *

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Initializes new instance of the {@code TextEditOptions} object with default options. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Gets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied.

**Returns:**
boolean value

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Gets mode for processing clipping path of the edited text.

**Returns:**
ClippingPathsProcessingMode element

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Gets mode that defines behavior for fonts replacement scenarios.

**Returns:**
FontReplace value @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Gets mode that defines behavior for language transformation scenarios.

**Returns:**
LanguageTransformation value @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Gets mode that defines behavior in case fonts don't contain requested characters.

**Returns:**
NoCharacterAction value @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Gets or sets font used for replacing if user font does not contain required character

**Returns:**
Font instance

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Gets or sets value that permits searching for text underlining on the page of source document. <p> (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this. </p>

**Returns:**
boolean value

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Sets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Gets mode for processing clipping path of the edited text.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Sets mode that defines behavior for fonts replacement scenarios.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Sets mode that defines behavior for language transformation scenarios.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Sets mode that defines behavior in case fonts don't contain requested characters.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Gets or sets font used for replacing if user font does not contain required character

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Gets or sets value that permits searching for text underlining on the page of source document. <p> (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this. </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
