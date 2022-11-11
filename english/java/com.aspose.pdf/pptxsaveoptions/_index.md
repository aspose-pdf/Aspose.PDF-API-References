---
title: PptxSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to SVG format
type: docs
weight: 292
url: /java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Save options for export to SVG format
## Constructors

| Constructor | Description |
| --- | --- |
| [PptxSaveOptions()](#PptxSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [getImageResolution()](#getImageResolution--) | Gets or sets the image resolution (dpi). |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [getSaveFormat()](#getSaveFormat--) | Format of data save. |
| [getSeparateImages()](#getSeparateImages--) | If set to true then images are separated from all other graphics |
| [getSlidesAsImages()](#getSlidesAsImages--) | If set to true then all the content is recognized as images (one per page) |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [isOptimizeTextBoxes()](#isOptimizeTextBoxes--) | Toggles text columns recognition |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [setImageResolution(int value)](#setImageResolution-int-) | Gets or sets the image resolution (dpi). |
| [setOptimizeTextBoxes(boolean value)](#setOptimizeTextBoxes-boolean-) | Toggles text columns recognition |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [setSeparateImages(boolean value)](#setSeparateImages-boolean-) | If set to true then images are separated from all other graphics |
| [setSlidesAsImages(boolean value)](#setSlidesAsImages-boolean-) | If set to true then all the content is recognized as images (one per page) |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PptxSaveOptions() {#PptxSaveOptions--}
```
public PptxSaveOptions()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

--------------------

```
public static void ConvertWithShowingProgress()
 {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("input.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("output.html", saveOptions);

 }
 public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.EventType)
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             System.out.println(string.Format("{0}  - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             System.out.println(string.Format("{0}  - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             System.out.println(string.Format("{0}  - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             System.out.println(string.Format("{0}  - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         default:
             break;
     }
  }
```

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) - ConversionProgressEventHandler instance
### getImageResolution() {#getImageResolution--}
```
public final int getImageResolution()
```


Gets or sets the image resolution (dpi). Default is 192 dpi.

**Returns:**
int - int value
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Returns:**
com.aspose.pdf.ConversionProgressEventsTranslator - ConversionProgressEventsTranslator instance
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Format of data save.

**Returns:**
[SaveFormat](../../com.aspose.pdf/saveformat) - SaveFormat value
### getSeparateImages() {#getSeparateImages--}
```
public boolean getSeparateImages()
```


If set to true then images are separated from all other graphics

**Returns:**
boolean - boolean value
### getSlidesAsImages() {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```


If set to true then all the content is recognized as images (one per page)

**Returns:**
boolean - boolean value
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
### isOptimizeTextBoxes() {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```


Toggles text columns recognition

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




### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Sets boolean value which indicates will Response object be closed after document saved into response.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value)
```


This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

--------------------

```
public static void ConvertWithShowingProgress()
 {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("input.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.CustomProgressHandler = new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole);
     doc.Save("output.html", saveOptions);

 }
 public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.EventType)
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             System.out.println(string.Format("{0}  - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             System.out.println(string.Format("{0}  - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             System.out.println(string.Format("{0}  - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             System.out.println(string.Format("{0}  - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         default:
             break;
     }
  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | ConversionProgressEventHandler instance |

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

### setImageResolution(int value) {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```


Gets or sets the image resolution (dpi). Default is 192 dpi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setOptimizeTextBoxes(boolean value) {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```


Toggles text columns recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | ConversionProgressEventsTranslator instance |

### setSeparateImages(boolean value) {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```


If set to true then images are separated from all other graphics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSlidesAsImages(boolean value) {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```


If set to true then all the content is recognized as images (one per page)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

