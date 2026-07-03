---
title: RenditionAction
second_title: Aspose.PDF for Java API Reference
description: A rendition action that controls the playing of multimedia content.
type: docs
weight: 4180
url: /java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

A rendition action that controls the playing of multimedia content.

## Constructors

| Constructor | Description |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Creates the rendition action. |

## Methods

| Method | Description |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Gets or sets JavaScript code associated with the action. |
| [getRendition](#getRendition--) | Gets or sets rendition associated with the action. |
| [getRenditionOperation](#getRenditionOperation--) | The operation to perform when the action is triggered. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Gets or sets JavaScript code associated with the action. |
| [setRenditionOperation](#setRenditionOperation-int-) | The operation to perform when the action is triggered. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Creates the rendition action.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Gets or sets JavaScript code associated with the action.

**Returns:**
String value

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Gets or sets rendition associated with the action.

**Returns:**
Rendition instance

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

The operation to perform when the action is triggered.

**Returns:**
RenditionOperation element

### setJavaScript {#setJavaScript-java.lang.String-}
Gets or sets JavaScript code associated with the action.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

The operation to perform when the action is triggered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | RenditionOperation element |
