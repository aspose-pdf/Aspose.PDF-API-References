---
title: GoToRemoteAction
second_title: Aspose.PDF for Java API Reference
description: Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.
type: docs
weight: 145
url: /java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction), [com.aspose.pdf.GoToAction](../../com.aspose.pdf/gotoaction)
```
public final class GoToRemoteAction extends GoToAction
```

Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.
## Constructors

| Constructor | Description |
| --- | --- |
| [GoToRemoteAction(String remotePdf, int remotePageNumber)](#GoToRemoteAction-java.lang.String-int-) | Initializes GoToRemoteAction object. |
| [GoToRemoteAction(String remotePdf, ExplicitDestination destination)](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | Initializes GoToRemoteAction object. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestination()](#getDestination--) | Gets the destination to jump to. |
| [getFile()](#getFile--) | Gets the specification of the file in which the destination is located. |
| [getNewWindow()](#getNewWindow--) | Gets a flag specifying whether to open the destination document in a new window. |
| [getNext()](#getNext--) | Next actions in sequence. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination to jump to. |
| [setFile(FileSpecification value)](#setFile-com.aspose.pdf.FileSpecification-) | Sets the specification of the file in which the destination is located. |
| [setNewWindow(int value)](#setNewWindow-int-) | Sets a flag specifying whether to open the destination document in a new window. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GoToRemoteAction(String remotePdf, int remotePageNumber) {#GoToRemoteAction-java.lang.String-int-}
```
public GoToRemoteAction(String remotePdf, int remotePageNumber)
```


Initializes GoToRemoteAction object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| remotePdf | java.lang.String | Destination PDF document. |
| remotePageNumber | int | Destination page number. |

### GoToRemoteAction(String remotePdf, ExplicitDestination destination) {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
```
public GoToRemoteAction(String remotePdf, ExplicitDestination destination)
```


Initializes GoToRemoteAction object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| remotePdf | java.lang.String | Destination PDF document. |
| destination | [ExplicitDestination](../../com.aspose.pdf/explicitdestination) | Destination in the PDF document. |

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
### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Gets the destination to jump to.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - destination to jump
### getFile() {#getFile--}
```
public FileSpecification getFile()
```


Gets the specification of the file in which the destination is located.

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification) - FileSpecification object
### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


Gets a flag specifying whether to open the destination document in a new window.

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




### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Sets the destination to jump to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | destination to jump |

### setFile(FileSpecification value) {#setFile-com.aspose.pdf.FileSpecification-}
```
public void setFile(FileSpecification value)
```


Sets the specification of the file in which the destination is located.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification value |

### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


Sets a flag specifying whether to open the destination document in a new window.

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

