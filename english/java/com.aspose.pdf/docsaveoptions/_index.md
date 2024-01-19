---
title: DocSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Doc format
type: docs
weight: 89
url: /java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)

**All Implemented Interfaces:**
[com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Save options for export to Doc format
## Constructors

| Constructor | Description |
| --- | --- |
| [DocSaveOptions()](#DocSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | This handler can be used to handle conversion progress events f.e. |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | This handler can be used to handle conversion progress events f.e. |
| [getMode()](#getMode--) | Recognition mode. |
| [setMode(int value)](#setMode-int-) | Recognition mode. |
| [getRelativeHorizontalProximity()](#getRelativeHorizontalProximity--) | In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. |
| [getMaxDistanceBetweenTextLines()](#getMaxDistanceBetweenTextLines--) | This parameter is used for grouping text lines into paragraphs. |
| [setMaxDistanceBetweenTextLines(float value)](#setMaxDistanceBetweenTextLines-float-) | This parameter is used for grouping text lines into paragraphs. |
| [setRelativeHorizontalProximity(float value)](#setRelativeHorizontalProximity-float-) | In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. |
| [isRecognizeBullets()](#isRecognizeBullets--) | Switch on the recognition of bullets. |
| [setRecognizeBullets(boolean value)](#setRecognizeBullets-boolean-) | Switch on the recognition of bullets. |
| [isAddReturnToLineEnd()](#isAddReturnToLineEnd--) | Is used paragraph or line breaks. |
| [setAddReturnToLineEnd(boolean value)](#setAddReturnToLineEnd-boolean-) | Use paragraph or line breaks |
| [getImageResolutionX()](#getImageResolutionX--) | Converted images X resolution. |
| [setImageResolutionX(int value)](#setImageResolutionX-int-) | Converted images X resolution. |
| [getImageResolutionY()](#getImageResolutionY--) | Converted images Y resolution. |
| [setImageResolutionY(int value)](#setImageResolutionY-int-) | Converted images Y resolution. |
| [getFormat()](#getFormat--) | Get output format |
| [setFormat(int value)](#setFormat-int-) | Set output format |
| [getBatchSize()](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setBatchSize(int value)](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getMemorySaveModePath()](#getMemorySaveModePath--) | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
| [setMemorySaveModePath(String value)](#setMemorySaveModePath-java.lang.String-) | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
### DocSaveOptions() {#DocSaveOptions--}
```
public DocSaveOptions()
```


Constructor

### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

--------------------

```
public static void convertWithShowingProgress()
 {
     (new License()).setLicense("License\\Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("Booklet.doc", saveOptions);
     System.in.read();
 }
 public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.getEventType())
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             Console.WriteLine("%s  - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             Console.WriteLine("%s  - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             Console.WriteLine("%s  - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             Console.WriteLine("{0}  - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         default:
             break;
     }
  }
```

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) - ConversionProgressEventHandler instance
### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)
```


This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

--------------------

```
public static void convertWithShowingProgress()
 {
     (new License()).setLicense("License\\Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("Booklet.doc", saveOptions);
     System.in.read();
 }
 public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.getEventType())
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             Console.WriteLine("%s  - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             Console.WriteLine("%s  - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             Console.WriteLine("%s  - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             Console.WriteLine("{0}  - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         default:
             break;
     }
  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProgressHandler | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | ConversionProgressEventHandler instance |

### getMode() {#getMode--}
```
public int getMode()
```


Recognition mode.

**Returns:**
int - RecognitionMode value
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Recognition mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | RecognitionMode value |

### getRelativeHorizontalProximity() {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```


In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document.

**Returns:**
float - Relative proximity
### getMaxDistanceBetweenTextLines() {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```


This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height.

**Returns:**
float - float value
### setMaxDistanceBetweenTextLines(float value) {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```


This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setRelativeHorizontalProximity(float value) {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```


In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | Relative proximity |

### isRecognizeBullets() {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```


Switch on the recognition of bullets.

**Returns:**
boolean - boolean value
### setRecognizeBullets(boolean value) {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```


Switch on the recognition of bullets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAddReturnToLineEnd() {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```


Is used paragraph or line breaks.

**Returns:**
boolean - boolean value.
### setAddReturnToLineEnd(boolean value) {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```


Use paragraph or line breaks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value. |

### getImageResolutionX() {#getImageResolutionX--}
```
public int getImageResolutionX()
```


Converted images X resolution.

**Returns:**
int - int value
### setImageResolutionX(int value) {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```


Converted images X resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getImageResolutionY() {#getImageResolutionY--}
```
public int getImageResolutionY()
```


Converted images Y resolution.

**Returns:**
int - int value
### setImageResolutionY(int value) {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```


Converted images Y resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getFormat() {#getFormat--}
```
public int getFormat()
```


Get output format

**Returns:**
int - DocFormat element
### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


Set output format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | DocFormat element |

### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int
### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMemorySaveModePath() {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```


Defines the path (file name or directory name) to hold temporary data when converting in memory save mode.

**Returns:**
java.lang.String - String value
### setMemorySaveModePath(String value) {#setMemorySaveModePath-java.lang.String-}
```
public final void setMemorySaveModePath(String value)
```


Defines the path (file name or directory name) to hold temporary data when converting in memory save mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

