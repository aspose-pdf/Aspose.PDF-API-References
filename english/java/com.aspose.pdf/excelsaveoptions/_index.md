---
title: ExcelSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Excel format
type: docs
weight: 101
url: /java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Save options for export to Excel format
## Constructors

| Constructor | Description |
| --- | --- |
| [ExcelSaveOptions()](#ExcelSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Output format. |
| [getMinimizeTheNumberOfWorksheets()](#getMinimizeTheNumberOfWorksheets--) | Set true if you need to minimize the number of worksheets in resultant workbook. |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [getSaveFormat()](#getSaveFormat--) | Format of data save. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [isInsertBlankColumnAtFirst()](#isInsertBlankColumnAtFirst--) | Set false if you need suppress inserting of blank column as the first column of worksheet. |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [isUniformWorksheets()](#isUniformWorksheets--) | Set true for using uniform columns division through the document. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [setFormat(int value)](#setFormat-int-) | Output format |
| [setInsertBlankColumnAtFirst(boolean value)](#setInsertBlankColumnAtFirst-boolean-) | Set false if you need suppress inserting of blank column as the first column of worksheet. |
| [setMinimizeTheNumberOfWorksheets(boolean value)](#setMinimizeTheNumberOfWorksheets-boolean-) | Set true if you need to minimize the number of worksheets in resultant workbook. |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [setUniformWorksheets(boolean value)](#setUniformWorksheets-boolean-) | Set true for using uniform columns division through the document. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExcelSaveOptions() {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
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
### getFormat() {#getFormat--}
```
public int getFormat()
```


Output format.

Return  ExcelSaveOptions.ExcelFormat.XMLSpreadSheet2003  or  ExcelSaveOptions.ExcelFormat.XLSX  or  ExcelSaveOptions.ExcelFormat.CSV 

**Returns:**
int - ExcelFormat element
### getMinimizeTheNumberOfWorksheets() {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```


Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet.

**Returns:**
boolean - boolean value
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
### isInsertBlankColumnAtFirst() {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```


Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted.

**Returns:**
boolean - boolean value
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean - boolean value
### isUniformWorksheets() {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```


Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page.

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


Output format

Use the  ExcelSaveOptions.ExcelFormat.XMLSpreadSheet2003  or  ExcelSaveOptions.ExcelFormat.XLSX 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ExcelFormat element |

### setInsertBlankColumnAtFirst(boolean value) {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```


Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMinimizeTheNumberOfWorksheets(boolean value) {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```


Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet.

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

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | boolean value |

### setUniformWorksheets(boolean value) {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```


Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

