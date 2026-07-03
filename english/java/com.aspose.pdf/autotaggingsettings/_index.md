---
title: AutoTaggingSettings
second_title: Aspose.PDF for Java API Reference
description: Provides settings for the auto-tagging functionality in PDF documents. The {@link AutoTaggingSettings} class allows configuring options for automatic tagging of PDF content. It.
type: docs
weight: 230
url: /java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Provides settings for the auto-tagging functionality in PDF documents. The {@link AutoTaggingSettings} class allows configuring options for automatic tagging of PDF content. It includes properties to enable or disable auto-tagging, specify a strategy for heading recognition, and define heading levels based on font sizes.

## Constructors

| Constructor | Description |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getDefault](#getDefault--) | Gets the default settings for auto-tagging functionality in PDF documents. The default settings enable auto-tagging and use the automatic strategy for heading recognition. These settings can be used as a baseline configuration for PDF format conversion or other operations requiring automatic tagging of PDF content. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Gets or sets a value indicating whether the auto-tagging functionality is enabled. When enabled, the auto-tagging functionality automatically generates tagged content for the PDF document, which can improve accessibility and structure. |
| [getHeadingLevels](#getHeadingLevels--) | Gets or sets the heading levels used for determining the structure of headings in a PDF document. The {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) property allows configuring the mapping of font sizes to heading levels. This is used during the auto-tagging process to identify and assign appropriate heading levels based on the font size of text elements in the document. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Gets or sets the strategy used for recognizing headings in the document during auto-tagging. The {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) property determines how headings are identified in the document. Available strategies include recognizing headings based on outlines, heuristic analysis, or automatic detection. Setting this property to {@link HeadingRecognitionStrategy#None} disables heading recognition. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Gets or sets a value indicating whether the auto-tagging functionality is enabled. When enabled, the auto-tagging functionality automatically generates tagged content for the PDF document, which can improve accessibility and structure. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Gets or sets the heading levels used for determining the structure of headings in a PDF document. The {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) property allows configuring the mapping of font sizes to heading levels. This is used during the auto-tagging process to identify and assign appropriate heading levels based on the font size of text elements in the document. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Gets or sets the strategy used for recognizing headings in the document during auto-tagging. The {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) property determines how headings are identified in the document. Available strategies include recognizing headings based on outlines, heuristic analysis, or automatic detection. Setting this property to {@link HeadingRecognitionStrategy#None} disables heading recognition. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Gets the default settings for auto-tagging functionality in PDF documents. The default settings enable auto-tagging and use the automatic strategy for heading recognition. These settings can be used as a baseline configuration for PDF format conversion or other operations requiring automatic tagging of PDF content.

**Returns:**
AutoTaggingSettings instance

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Gets or sets a value indicating whether the auto-tagging functionality is enabled. When enabled, the auto-tagging functionality automatically generates tagged content for the PDF document, which can improve accessibility and structure.

**Returns:**
boolean value

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Gets or sets the heading levels used for determining the structure of headings in a PDF document. The {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) property allows configuring the mapping of font sizes to heading levels. This is used during the auto-tagging process to identify and assign appropriate heading levels based on the font size of text elements in the document.

**Returns:**
HeadingLevels instance

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Gets or sets the strategy used for recognizing headings in the document during auto-tagging. The {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) property determines how headings are identified in the document. Available strategies include recognizing headings based on outlines, heuristic analysis, or automatic detection. Setting this property to {@link HeadingRecognitionStrategy#None} disables heading recognition.

**Returns:**
HeadingRecognitionStrategy element

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Gets or sets a value indicating whether the auto-tagging functionality is enabled. When enabled, the auto-tagging functionality automatically generates tagged content for the PDF document, which can improve accessibility and structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Gets or sets the heading levels used for determining the structure of headings in a PDF document. The {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) property allows configuring the mapping of font sizes to heading levels. This is used during the auto-tagging process to identify and assign appropriate heading levels based on the font size of text elements in the document.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Gets or sets the strategy used for recognizing headings in the document during auto-tagging. The {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) property determines how headings are identified in the document. Available strategies include recognizing headings based on outlines, heuristic analysis, or automatic detection. Setting this property to {@link HeadingRecognitionStrategy#None} disables heading recognition.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | HeadingRecognitionStrategy element |
