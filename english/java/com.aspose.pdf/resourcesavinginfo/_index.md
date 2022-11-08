---
title: SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to external resource files saving that occures during conversion of PDF to some other format f.e.
type: docs
weight: 16
url: /java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object
```
public static class SaveOptions.ResourceSavingInfo
```

This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML)
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | Set by converter. |
| [getResourceType()](#getResourceType--) | Set by converter. |
| [getSupposedFileName()](#getSupposedFileName--) | Set by converter. |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

