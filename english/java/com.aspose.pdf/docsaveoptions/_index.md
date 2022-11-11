---
title: DocSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Doc format
type: docs
weight: 90
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBatchSize()](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [getFormat()](#getFormat--) | Get output format |
| [getImageResolutionX()](#getImageResolutionX--) | Converted images X resolution. |
| [getImageResolutionY()](#getImageResolutionY--) | Converted images Y resolution. |
| [getMaxDistanceBetweenTextLines()](#getMaxDistanceBetweenTextLines--) | This parameter is used for grouping text lines into paragraphs. |
| [getMemorySaveModePath()](#getMemorySaveModePath--) | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
| [getMode()](#getMode--) | Recognition mode. |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [getRelativeHorizontalProximity()](#getRelativeHorizontalProximity--) | In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. |
| [getSaveFormat()](#getSaveFormat--) | Format of data save. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isAddReturnToLineEnd()](#isAddReturnToLineEnd--) | Is used paragraph or line breaks. |
| [isCloseResponse()](#isCloseResponse--) | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [isRecognizeBullets()](#isRecognizeBullets--) | Switch on the recognition of bullets. |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddReturnToLineEnd(boolean value)](#setAddReturnToLineEnd-boolean-) | Use paragraph or line breaks |
| [setBatchSize(int value)](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [setFormat(int value)](#setFormat-int-) | Set output format |
| [setImageResolutionX(int value)](#setImageResolutionX-int-) | Converted images X resolution. |
| [setImageResolutionY(int value)](#setImageResolutionY-int-) | Converted images Y resolution. |
| [setMaxDistanceBetweenTextLines(float value)](#setMaxDistanceBetweenTextLines-float-) | This parameter is used for grouping text lines into paragraphs. |
| [setMemorySaveModePath(String value)](#setMemorySaveModePath-java.lang.String-) | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
| [setMode(int value)](#setMode-int-) | Recognition mode. |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [setRecognizeBullets(boolean value)](#setRecognizeBullets-boolean-) | Switch on the recognition of bullets. |
| [setRelativeHorizontalProximity(float value)](#setRelativeHorizontalProximity-float-) | In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocSaveOptions() {#DocSaveOptions--}
```
public DocSaveOptions()
```


Constructor

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
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getFormat() {#getFormat--}
```
public int getFormat()
```


Get output format

**Returns:**
int - DocFormat element
### getImageResolutionX() {#getImageResolutionX--}
```
public int getImageResolutionX()
```


Converted images X resolution.

**Returns:**
int - int value
### getImageResolutionY() {#getImageResolutionY--}
```
public int getImageResolutionY()
```


Converted images Y resolution.

**Returns:**
int - int value
### getMaxDistanceBetweenTextLines() {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```


This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height.

**Returns:**
float - float value
### getMemorySaveModePath() {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```


Defines the path (file name or directory name) to hold temporary data when converting in memory save mode.

**Returns:**
java.lang.String - String value
### getMode() {#getMode--}
```
public int getMode()
```


Recognition mode.

**Returns:**
int - RecognitionMode value
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Returns:**
com.aspose.pdf.ConversionProgressEventsTranslator - ConversionProgressEventsTranslator instance
### getRelativeHorizontalProximity() {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```


In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document.

**Returns:**
float - Relative proximity
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Format of data save.

**Returns:**
[SaveFormat](../../com.aspose.pdf/saveformat) - SaveFormat value
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAddReturnToLineEnd() {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```


Is used paragraph or line breaks.

**Returns:**
boolean - boolean value.
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


Gets boolean value which indicates will Response object be closed after document saved into response.

**Returns:**
boolean - boolean value
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer.

Value:  true  text will be extracted in result document; otherwise,  false .

**Returns:**
boolean - boolean value
### isRecognizeBullets() {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```


Switch on the recognition of bullets.

**Returns:**
boolean - boolean value
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddReturnToLineEnd(boolean value) {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```


Use paragraph or line breaks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value. |

### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Sets boolean value which indicates will Response object be closed after document saved into response.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

### setExtractOcrSublayerOnly(boolean value) {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```


This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer.

Value:  true  text will be extracted in result document; otherwise,  false .

--------------------

Default value == false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


Set output format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | DocFormat element |

### setImageResolutionX(int value) {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```


Converted images X resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setImageResolutionY(int value) {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```


Converted images Y resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setMaxDistanceBetweenTextLines(float value) {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```


This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setMemorySaveModePath(String value) {#setMemorySaveModePath-java.lang.String-}
```
public final void setMemorySaveModePath(String value)
```


Defines the path (file name or directory name) to hold temporary data when converting in memory save mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Recognition mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | RecognitionMode value |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | ConversionProgressEventsTranslator instance |

### setRecognizeBullets(boolean value) {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```


Switch on the recognition of bullets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRelativeHorizontalProximity(float value) {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```


In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | Relative proximity |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | boolean value |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

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

