---
title: HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to external resource image files saving during PDF to HTML conversion.
type: docs
weight: 17
url: /java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions.ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo)
```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlImageSavingInfo()](#HtmlImageSavingInfo--) | creates new instance of HtmlImageSavingInfo |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | Set by converter. |
| [getHtmlHostPageNumber()](#getHtmlHostPageNumber--) | Tells to custom code to what page of generated set of HTML page-files pertains saved image. |
| [getImageType()](#getImageType--) | Represents type of saved image referenced in HTML. |
| [getParentType()](#getParentType--) | Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. |
| [getPdfHostPageNumber()](#getPdfHostPageNumber--) | Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. |
| [getResourceType()](#getResourceType--) | Set by converter. |
| [getSupposedFileName()](#getSupposedFileName--) | Set by converter. |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. |
| [setHtmlHostPageNumber(int htmlHostPageNumber)](#setHtmlHostPageNumber-int-) | Tells to custom code to what page of generated set of HTML page-files pertains saved image. |
| [setImageType(int imageType)](#setImageType-int-) | Represents type of saved image referenced in HTML. |
| [setParentType(int parentType)](#setParentType-int-) | Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. |
| [setPdfHostPageNumber(int pdfHostPageNumber)](#setPdfHostPageNumber-int-) | Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlImageSavingInfo() {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```


creates new instance of HtmlImageSavingInfo

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
### getContentStream() {#getContentStream--}
```
public byte[] getContentStream()
```


Set by converter. Represents binary content of saved file.

**Returns:**
byte[] - array of bytes
### getHtmlHostPageNumber() {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```


Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated.

**Returns:**
int - int value
### getImageType() {#getImageType--}
```
public int getImageType()
```


Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done

**Returns:**
int - HtmlImageType element
### getParentType() {#getParentType--}
```
public int getParentType()
```


Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content).

**Returns:**
int - ImageParentTypes element
### getPdfHostPageNumber() {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```


Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is unknown, it always return '1'

**Returns:**
int - int value
### getResourceType() {#getResourceType--}
```
public int getResourceType()
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file

**Returns:**
int - NodeLevelResourceType element
### getSupposedFileName() {#getSupposedFileName--}
```
public String getSupposedFileName()
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCustomProcessingCancelled() {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```


this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file).

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




### setCustomProcessingCancelled(boolean customProcessingCancelled) {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```


this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both senses - for saving somewhere and for naming in referencing file).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProcessingCancelled | boolean | boolean value |

### setHtmlHostPageNumber(int htmlHostPageNumber) {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```


Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlHostPageNumber | int | int value |

### setImageType(int imageType) {#setImageType-int-}
```
public void setImageType(int imageType)
```


Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageType | int | HtmlImageType element |

### setParentType(int parentType) {#setParentType-int-}
```
public void setParentType(int parentType)
```


Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentType | int | ImageParentTypes element |

### setPdfHostPageNumber(int pdfHostPageNumber) {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```


Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is unknown, it always return '1'

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfHostPageNumber | int | int value |

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

