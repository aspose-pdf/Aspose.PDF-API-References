---
title: DocSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Doc format
type: docs
weight: 1030
url: /java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Save options for export to Doc format

## Constructors

| Constructor | Description |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Get output format |
| [getImageResolutionX](#getImageResolutionX--) | Converted images X resolution. |
| [getImageResolutionY](#getImageResolutionY--) | Converted images Y resolution. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
| [getMode](#getMode--) | Recognition mode. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Is used paragraph or line breaks. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Gets or sets conversion for Type3 fonts. In Type 3 fonts, glyphs shall be defined by streams of graphics operators. This means that in the DOC/DOCX output we see images instead of text. Set this flag to true to convert Type3 fonts to TTF and get text in the resulting file. |
| [isRecognizeBullets](#isRecognizeBullets--) | Switch on the recognition of bullets. |
| [isReSaveFonts](#isReSaveFonts--) | Gets or sets the procedure for resaving fonts. If set to true, we reload fonts on every page to avoid the influence of previous font properties and load the newly created font from scratch. Set this option to false if you want to improve performance. The default value is true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Use paragraph or line breaks |
| [setBatchSize](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Gets or sets conversion for Type3 fonts. In Type 3 fonts, glyphs shall be defined by streams of graphics operators. This means that in the DOC/DOCX output we see images instead of text. Set this flag to true to convert Type3 fonts to TTF and get text in the resulting file. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | This handler can be used to handle conversion progress events f.e. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Set output format |
| [setImageResolutionX](#setImageResolutionX-int-) | Converted images X resolution. |
| [setImageResolutionY](#setImageResolutionY-int-) | Converted images Y resolution. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Recognition mode. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Switch on the recognition of bullets. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Gets or sets the procedure for resaving fonts. If set to true, we reload fonts on every page to avoid the influence of previous font properties and load the newly created font from scratch. Set this option to false if you want to improve performance. The default value is true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Constructor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int value

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler instance

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Get output format

**Returns:**
DocFormat element @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Converted images X resolution.

**Returns:**
int value

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Converted images Y resolution.

**Returns:**
int value

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height.

**Returns:**
float value

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Defines the path (file name or directory name) to hold temporary data when converting in memory save mode.

**Returns:**
String value

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Recognition mode.

**Returns:**
RecognitionMode value @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document.

**Returns:**
Relative proximity

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Is used paragraph or line breaks.

**Returns:**
boolean value.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Gets or sets conversion for Type3 fonts. In Type 3 fonts, glyphs shall be defined by streams of graphics operators. This means that in the DOC/DOCX output we see images instead of text. Set this flag to true to convert Type3 fonts to TTF and get text in the resulting file.

**Returns:**
boolean value

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Switch on the recognition of bullets.

**Returns:**
boolean value

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Gets or sets the procedure for resaving fonts. If set to true, we reload fonts on every page to avoid the influence of previous font properties and load the newly created font from scratch. Set this option to false if you want to improve performance. The default value is true;

**Returns:**
boolean value

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Use paragraph or line breaks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Gets or sets conversion for Type3 fonts. In Type 3 fonts, glyphs shall be defined by streams of graphics operators. This means that in the DOC/DOCX output we see images instead of text. Set this flag to true to convert Type3 fonts to TTF and get text in the resulting file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
This handler can be used to handle conversion progress events f.e.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Set output format

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Converted images X resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Converted images Y resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Defines the path (file name or directory name) to hold temporary data when converting in memory save mode.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Recognition mode.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Switch on the recognition of bullets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | Relative proximity |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Gets or sets the procedure for resaving fonts. If set to true, we reload fonts on every page to avoid the influence of previous font properties and load the newly created font from scratch. Set this option to false if you want to improve performance. The default value is true;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
