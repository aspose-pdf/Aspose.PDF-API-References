---
title: LaunchAction
second_title: Aspose.PDF for Java API Reference
description: Represents a launch action that launches an application or opens or prints a document.
type: docs
weight: 190
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
| [getFile()](#getFile--) | Gets the application to be launched or the document to be opened or printed. |
| [setFile(String value)](#setFile-java.lang.String-) | Sets the application to be launched or the document to be opened or printed. |
| [getNewWindow()](#getNewWindow--) | Gets a flag specifying whether to open the destination document in a new window (affect PDF documents only). |
| [setNewWindow(int value)](#setNewWindow-int-) | Sets a flag specifying whether to open the destination document in a new window (affect PDF documents only). |
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

### getFile() {#getFile--}
```
public String getFile()
```


Gets the application to be launched or the document to be opened or printed.

**Returns:**
java.lang.String - String value
### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


Sets the application to be launched or the document to be opened or printed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


Gets a flag specifying whether to open the destination document in a new window (affect PDF documents only).

**Returns:**
int - ExtendedBoolean element
### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


Sets a flag specifying whether to open the destination document in a new window (affect PDF documents only). ExtendedBoolean

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ExtendedBoolean element |

