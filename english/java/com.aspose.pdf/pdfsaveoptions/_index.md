---
title: PdfSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Pdf format
type: docs
weight: 280
url: /java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Save options for export to Pdf format
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Font name used by default for fonts which are absent on computer. |
| [getSaveFormat()](#getSaveFormat--) | Format of data save. |
| [getTempPath()](#getTempPath--) | Path for temporary files. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Font name used by default for fonts which are absent on computer. |
| [setTempPath(String value)](#setTempPath-java.lang.String-) | Path for temporary files. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getDefaultFontName() {#getDefaultFontName--}
```
public String getDefaultFontName()
```


Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with  DefaultFontName  is found on device)

**Returns:**
java.lang.String - String value
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Format of data save.

**Returns:**
[SaveFormat](../../com.aspose.pdf/saveformat) - SaveFormat value
### getTempPath() {#getTempPath--}
```
public final String getTempPath()
```


Path for temporary files.

**Returns:**
java.lang.String - String value
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

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public void setDefaultFontName(String value)
```


Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with  DefaultFontName  is found on device)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setTempPath(String value) {#setTempPath-java.lang.String-}
```
public final void setTempPath(String value)
```


Path for temporary files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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

