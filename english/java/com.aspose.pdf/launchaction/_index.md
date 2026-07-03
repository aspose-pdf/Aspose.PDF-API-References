---
title: LaunchAction
second_title: Aspose.PDF for Java API Reference
description: Represents a launch action that launches an application or opens or prints a document.
type: docs
weight: 2620
url: /java/com.aspose.pdf/launchaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.LaunchAction, com.aspose.pdf.PdfAction, com.aspose.pdf.LaunchAction

**All Implemented Interfaces:**
IAppointment

```
public final class LaunchAction extends PdfAction
```

Represents a launch action that launches an application or opens or prints a document.

## Constructors

| Constructor | Description |
| --- | --- |
| [LaunchAction](#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-) | Creates a launch action. |
| [LaunchAction](#LaunchAction-java.lang.String-) | Creates a launch action. |

## Methods

| Method | Description |
| --- | --- |
| [getFile](#getFile--) | Gets the application to be launched or the document to be opened or printed. |
| [getNewWindow](#getNewWindow--) | Gets a flag specifying whether to open the destination document in a new window (affect PDF documents only). |
| [setFile](#setFile-java.lang.String-) | Sets the application to be launched or the document to be opened or printed. |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | Sets a flag specifying whether to open the destination document in a new window (affect PDF documents only). ExtendedBoolean |

### LaunchAction {#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-}
Creates a launch action.

### LaunchAction {#LaunchAction-java.lang.String-}
Creates a launch action.

### getFile {#getFile--}
```
public String getFile()
```

Gets the application to be launched or the document to be opened or printed.

**Returns:**
String value

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

Gets a flag specifying whether to open the destination document in a new window (affect PDF documents only).

**Returns:**
ExtendedBoolean element @see ExtendedBoolean

### setFile {#setFile-java.lang.String-}
Sets the application to be launched or the document to be opened or printed.

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
Sets a flag specifying whether to open the destination document in a new window (affect PDF documents only). ExtendedBoolean
