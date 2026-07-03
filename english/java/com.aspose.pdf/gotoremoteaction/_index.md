---
title: GoToRemoteAction
linktitle: GoToRemoteAction
second_title: Aspose.PDF for Java API Reference
description: Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.
type: docs
weight: 1820
url: /java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.GoToAction, com.aspose.pdf.GoToRemoteAction

**All Implemented Interfaces:**
IAppointment

```
public final class GoToRemoteAction extends GoToAction
```

Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.

## Constructors

| Constructor | Description |
| --- | --- |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | Initializes GoToRemoteAction object. |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-int-) | Initializes GoToRemoteAction object. |

## Methods

| Method | Description |
| --- | --- |
| [getFile](#getFile--) | Gets the specification of the file in which the destination is located. |
| [getNewWindow](#getNewWindow--) | Gets a flag specifying whether to open the destination document in a new window. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | / * / * Gets the destination to jump to. / * / * / * |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Sets the specification of the file in which the destination is located. |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | Sets a flag specifying whether to open the destination document in a new window. |

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
Initializes GoToRemoteAction object.

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-int-}
Initializes GoToRemoteAction object.

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Gets the specification of the file in which the destination is located.

**Returns:**
FileSpecification object

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

Gets a flag specifying whether to open the destination document in a new window.

**Returns:**
ExtendedBoolean element @see ExtendedBoolean

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
/ * / * Gets the destination to jump to. / * / * / *

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Sets the specification of the file in which the destination is located.

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
Sets a flag specifying whether to open the destination document in a new window.
