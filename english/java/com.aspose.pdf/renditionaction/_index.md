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
| [getRendition()](#getRendition--) | Gets or sets rendition associated with the action. |
| [getRenditionOperation()](#getRenditionOperation--) | The operation to perform when the action is triggered. |
| [setRenditionOperation(int value)](#setRenditionOperation-int-) | The operation to perform when the action is triggered. |
| [getJavaScript()](#getJavaScript--) | Gets or sets JavaScript code associated with the action. |
| [setJavaScript(String value)](#setJavaScript-java.lang.String-) | Gets or sets JavaScript code associated with the action. |
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
### setRenditionOperation(int value) {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```


The operation to perform when the action is triggered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | RenditionOperation element |

### getJavaScript() {#getJavaScript--}
```
public final String getJavaScript()
```


Gets or sets JavaScript code associated with the action.

**Returns:**
java.lang.String - String value
### setJavaScript(String value) {#setJavaScript-java.lang.String-}
```
public final void setJavaScript(String value)
```


Gets or sets JavaScript code associated with the action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Staring value |

