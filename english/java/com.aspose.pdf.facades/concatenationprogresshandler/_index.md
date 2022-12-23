---
title: PdfFileEditor.ConcatenationProgressHandler
second_title: Aspose.PDF for Java API Reference
description: Represents class with abstract method that usually supplied by calling side and handles progress events that comes from concatenation.
type: docs
weight: 11
url: /java/com.aspose.pdf.facades/pdffileeditor.concatenationprogresshandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class PdfFileEditor.ConcatenationProgressHandler extends System.MulticastDelegate
```

Represents class with abstract method that usually supplied by calling side and handles progress events that comes from concatenation. Usually such supplied customer's handler can be used to show total concatenation progress on console or in progress bar.

represents information about occurred progress event
## Constructors

| Constructor | Description |
| --- | --- |
| [ConcatenationProgressHandler()](#ConcatenationProgressHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(PdfFileEditor.ProgressEventHandlerInfo eventInfo)](#invoke-com.aspose.pdf.facades.PdfFileEditor.ProgressEventHandlerInfo-) |  |
### ConcatenationProgressHandler() {#ConcatenationProgressHandler--}
```
public ConcatenationProgressHandler()
```


### invoke(PdfFileEditor.ProgressEventHandlerInfo eventInfo) {#invoke-com.aspose.pdf.facades.PdfFileEditor.ProgressEventHandlerInfo-}
```
public abstract void invoke(PdfFileEditor.ProgressEventHandlerInfo eventInfo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventInfo | [ProgressEventHandlerInfo](../../com.aspose.pdf.facades/progresseventhandlerinfo) |  |

