---
title: GoToRemoteAction
second_title: Aspose.PDF for Java API Reference
description: Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.
type: docs
weight: 123
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
| [GoToRemoteAction(String remotePdf, int remotePageNumber)](#GoToRemoteAction-java.lang.String-int-) |  |
| [GoToRemoteAction(String remotePdf, ExplicitDestination destination)](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFile()](#getFile--) | Gets the specification of the file in which the destination is located. |
| [setFile(FileSpecification value)](#setFile-com.aspose.pdf.FileSpecification-) | Sets the specification of the file in which the destination is located. |
| [getNewWindow()](#getNewWindow--) | Gets a flag specifying whether to open the destination document in a new window. |
| [setNewWindow(int value)](#setNewWindow-int-) | Sets a flag specifying whether to open the destination document in a new window. |
| [getDestination()](#getDestination--) | Gets or sets the destination to jump to. |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) |  |
### GoToRemoteAction(String remotePdf, int remotePageNumber) {#GoToRemoteAction-java.lang.String-int-}
```
public GoToRemoteAction(String remotePdf, int remotePageNumber)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| remotePdf | java.lang.String |  |
| remotePageNumber | int |  |

### GoToRemoteAction(String remotePdf, ExplicitDestination destination) {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
```
public GoToRemoteAction(String remotePdf, ExplicitDestination destination)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| remotePdf | java.lang.String |  |
| destination | [ExplicitDestination](../../com.aspose.pdf/explicitdestination) |  |

### getFile() {#getFile--}
```
public FileSpecification getFile()
```


Gets the specification of the file in which the destination is located.

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification)
### setFile(FileSpecification value) {#setFile-com.aspose.pdf.FileSpecification-}
```
public void setFile(FileSpecification value)
```


Sets the specification of the file in which the destination is located.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) |  |

### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


Gets a flag specifying whether to open the destination document in a new window.

**Returns:**
int
### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


Sets a flag specifying whether to open the destination document in a new window.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Gets or sets the destination to jump to.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment)
### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Sets the destination to jump to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) |  |

