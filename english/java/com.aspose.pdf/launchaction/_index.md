---
title: LaunchAction
second_title: Aspose.PDF for Java API Reference
description: Represents a launch action that launches an application or opens or prints a document.
type: docs
weight: 187
url: /java/com.aspose.pdf/launchaction/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class LaunchAction extends PdfAction
```

Represents a launch action that launches an application or opens or prints a document.
## Constructors

| Constructor | Description |
| --- | --- |
| [LaunchAction(String file)](#LaunchAction-java.lang.String-) | Creates a launch action. |
| [LaunchAction(IDocument document, String file)](#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-) | Creates a launch action. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFile()](#getFile--) | Gets the application to be launched or the document to be opened or printed. |
| [getNewWindow()](#getNewWindow--) | Gets a flag specifying whether to open the destination document in a new window (affect PDF documents only). |
| [getNext()](#getNext--) | Next actions in sequence. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFile(String value)](#setFile-java.lang.String-) | Sets the application to be launched or the document to be opened or printed. |
| [setNewWindow(int value)](#setNewWindow-int-) | Sets a flag specifying whether to open the destination document in a new window (affect PDF documents only). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LaunchAction(String file) {#LaunchAction-java.lang.String-}
```
public LaunchAction(String file)
```


Creates a launch action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | The file to be launched. |

### LaunchAction(IDocument document, String file) {#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-}
```
public LaunchAction(IDocument document, String file)
```


Creates a launch action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where action will be created. |
| file | java.lang.String | The file to be launched. |

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
### getFile() {#getFile--}
```
public String getFile()
```


Gets the application to be launched or the document to be opened or printed.

**Returns:**
java.lang.String - String value
### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


Gets a flag specifying whether to open the destination document in a new window (affect PDF documents only).

**Returns:**
int - ExtendedBoolean element
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Next actions in sequence.

**Returns:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - ActionCollection object
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




### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


Sets the application to be launched or the document to be opened or printed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


Sets a flag specifying whether to open the destination document in a new window (affect PDF documents only). ExtendedBoolean

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ExtendedBoolean element |

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

