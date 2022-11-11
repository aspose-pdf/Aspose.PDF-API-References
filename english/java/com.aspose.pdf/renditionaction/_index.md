---
title: RenditionAction
second_title: Aspose.PDF for Java API Reference
description: A rendition action that controls the playing of multimedia content.
type: docs
weight: 306
url: /java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class RenditionAction extends PdfAction
```

A rendition action that controls the playing of multimedia content.
## Constructors

| Constructor | Description |
| --- | --- |
| [RenditionAction(String mediaFile, ScreenAnnotation screen)](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Creates the rendition action. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getJavaScript()](#getJavaScript--) | Gets or sets JavaScript code associated with the action. |
| [getNext()](#getNext--) | Next actions in sequence. |
| [getRendition()](#getRendition--) | Gets or sets rendition associated with the action. |
| [getRenditionOperation()](#getRenditionOperation--) | The operation to perform when the action is triggered. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setJavaScript(String value)](#setJavaScript-java.lang.String-) | Gets or sets JavaScript code associated with the action. |
| [setRenditionOperation(int value)](#setRenditionOperation-int-) | The operation to perform when the action is triggered. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenditionAction(String mediaFile, ScreenAnnotation screen) {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
```
public RenditionAction(String mediaFile, ScreenAnnotation screen)
```


Creates the rendition action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mediaFile | java.lang.String | The path to multimedia file. |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | The ScreenAnnotation object the RenditionAction will be bound with. |

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
### getJavaScript() {#getJavaScript--}
```
public final String getJavaScript()
```


Gets or sets JavaScript code associated with the action.

**Returns:**
java.lang.String - String value
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Next actions in sequence.

**Returns:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - ActionCollection object
### getRendition() {#getRendition--}
```
public final Rendition getRendition()
```


Gets or sets rendition associated with the action.

**Returns:**
[Rendition](../../com.aspose.pdf/rendition) - Rendition instance
### getRenditionOperation() {#getRenditionOperation--}
```
public final int getRenditionOperation()
```


The operation to perform when the action is triggered.

**Returns:**
int - RenditionOperation element
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setJavaScript(String value) {#setJavaScript-java.lang.String-}
```
public final void setJavaScript(String value)
```


Gets or sets JavaScript code associated with the action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Staring value |

### setRenditionOperation(int value) {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```


The operation to perform when the action is triggered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | RenditionOperation element |

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

