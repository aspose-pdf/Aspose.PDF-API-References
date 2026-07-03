---
title: MarkdownSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Represents the document save option class in the markdown format.
type: docs
weight: 60
url: /java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Represents the document save option class in the markdown format.

## Constructors

| Constructor | Description |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Creates an instance option to save a document in markdown format. |

## Methods

| Method | Description |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Get or set an rectangle area to extract content to markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Gets or sets the style of emphasis for generated document. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Gets and sets a property indicating whether vector graphics should be extracted. |
| [getHeadingLevels](#getHeadingLevels--) | Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition {@link HeadingRecognitionStrategy#Heuristic} strategy will be selected when set {@link HeadingRecognitionStrategy#Auto} strategies even if the document contains bookmarks. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Gets or sets the heading recognition strategy. |
| [getHeadingStyle](#getHeadingStyle--) | Gets or sets the heading style for generated document. |
| [getLineBreakStyle](#getLineBreakStyle--) | Gets or sets the line break style for generated document. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Gets and sets the directory name to save document resources such as images. This directory will be automatically created in the directory with the saved markdown file. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Gets ans sets allowance to convert subscript and superscript. This value is true by default. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Get or set an rectangle area to extract content to markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Gets or sets the style of emphasis for generated document. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Gets and sets a property indicating whether vector graphics should be extracted. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition {@link HeadingRecognitionStrategy#Heuristic} strategy will be selected when set {@link HeadingRecognitionStrategy#Auto} strategies even if the document contains bookmarks. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Gets or sets the heading recognition strategy. |
| [setHeadingStyle](#setHeadingStyle-int-) | Gets or sets the heading style for generated document. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Gets or sets the line break style for generated document. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Gets and sets the directory name to save document resources such as images. This directory will be automatically created in the directory with the saved markdown file. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Gets ans sets allowance to convert subscript and superscript. This value is true by default. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Creates an instance option to save a document in markdown format.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Get or set an rectangle area to extract content to markdown.

**Returns:**
Rectangle instance

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Gets or sets the style of emphasis for generated document.

**Returns:**
EmphasisStyle element

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Gets and sets a property indicating whether vector graphics should be extracted.

**Returns:**
boolean value

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition {@link HeadingRecognitionStrategy#Heuristic} strategy will be selected when set {@link HeadingRecognitionStrategy#Auto} strategies even if the document contains bookmarks.

**Returns:**
HeadingLevels instance

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Gets or sets the heading recognition strategy.

**Returns:**
HeadingRecognitionStrategy element

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Gets or sets the heading style for generated document.

**Returns:**
HeadingStyle element

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Gets or sets the line break style for generated document.

**Returns:**
LineBreakStyle element

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file.

**Returns:**
String value

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Gets and sets the directory name to save document resources such as images. This directory will be automatically created in the directory with the saved markdown file.

**Returns:**
String value

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Gets ans sets allowance to convert subscript and superscript. This value is true by default.

**Returns:**
boolean value

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image.

**Returns:**
boolean value

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Get or set an rectangle area to extract content to markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Gets or sets the style of emphasis for generated document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | EmphasisStyle element |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Gets and sets a property indicating whether vector graphics should be extracted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition {@link HeadingRecognitionStrategy#Heuristic} strategy will be selected when set {@link HeadingRecognitionStrategy#Auto} strategies even if the document contains bookmarks.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Gets or sets the heading recognition strategy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | HeadingRecognitionStrategy element |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Gets or sets the heading style for generated document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | HeadingStyle element |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Gets or sets the line break style for generated document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | LineBreakStyle element |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Gets and sets the directory name to save document resources such as images. This directory will be automatically created in the directory with the saved markdown file.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Gets ans sets allowance to convert subscript and superscript. This value is true by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
