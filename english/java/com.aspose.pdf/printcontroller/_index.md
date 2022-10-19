---
title: PrintController
second_title: Aspose.PDF for Java API Reference
description: Represents print controller.
type: docs
weight: 295
url: /java/com.aspose.pdf/printcontroller/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Drawing.Printing.PrintController

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class PrintController extends System.Drawing.Printing.PrintController implements System.IDisposable
```

Represents print controller.
## Constructors

| Constructor | Description |
| --- | --- |
| [PrintController()](#PrintController--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFileName()](#getFileName--) | Set file name |
| [setFileName(String value)](#setFileName-java.lang.String-) | Set file name |
| [onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onStartPagePublic-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | For internal usage only |
| [onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onStartPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | For internal usage only |
| [onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)](#onStartPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-) | For internal usage only |
| [onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onEndPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | For internal usage only |
| [onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)](#onEndPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-) | For internal usage only |
| [dispose()](#dispose--) | dispose instance |
### PrintController() {#PrintController--}
```
public PrintController()
```


### getFileName() {#getFileName--}
```
public final String getFileName()
```


Set file name

**Returns:**
java.lang.String - String value
### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Set file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onStartPagePublic-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public Graphics2D onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


For internal usage only

Fires on page start printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Internal instance ( Document to print) |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | Internal instance (Event arguments) |

**Returns:**
java.awt.Graphics2D - Graphics2D instance with printed page.
### onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onStartPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public System.Drawing.Graphics onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


For internal usage only

Fires on page start printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Internal instance ( Document to print) |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | Internal instance (Event arguments) |

**Returns:**
com.aspose.ms.System.Drawing.Graphics - Internal instance
### onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e) {#onStartPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-}
```
public void onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)
```


For internal usage only

Fires on page start printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Internal instance ( Document to print) |
| e | com.aspose.ms.System.Drawing.Printing.PrintEventArgs | Internal instance (Event arguments) |

### onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onEndPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public void onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


For internal usage only

Fires on page end printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Internal instance ( Document to print) |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | Internal instance (Event arguments) |

### onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e) {#onEndPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-}
```
public void onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)
```


For internal usage only

Fires on page end printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Internal instance ( Document to print) |
| e | com.aspose.ms.System.Drawing.Printing.PrintEventArgs | Internal instance (Event arguments) |

### dispose() {#dispose--}
```
public final void dispose()
```


dispose instance

