---
title: UnifiedSaveOptions.ConversionProgressEventHandler
second_title: Aspose.PDF for Java API Reference
description: Represents class with abstract method that usually supplied by calling side and handles progress events that comes from converter.
type: docs
weight: 10
url: /java/com.aspose.pdf/unifiedsaveoptions.conversionprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class UnifiedSaveOptions.ConversionProgressEventHandler extends System.MulticastDelegate
```

Represents class with abstract method that usually supplied by calling side and handles progress events that comes from converter. Usually such supplied customer's handler can be used to show total conversion progress on console or in progress bar.
## Constructors

| Constructor | Description |
| --- | --- |
| [ConversionProgressEventHandler()](#ConversionProgressEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo)](#invoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-) | Represents class with abstract method that usually supplied by calling side and handles progress events that comes from converter. |
| [beginInvoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | internal method |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | internal method |
| [isEmpty()](#isEmpty--) |  |
### ConversionProgressEventHandler() {#ConversionProgressEventHandler--}
```
public ConversionProgressEventHandler()
```


### invoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {#invoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-}
```
public abstract void invoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo)
```


Represents class with abstract method that usually supplied by calling side and handles progress events that comes from converter. Usually such supplied customer's handler can be used to show total conversion progress on console or in progress bar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventInfo | [ProgressEventHandlerInfo](../../com.aspose.pdf/progresseventhandlerinfo) | represents information about occurred progress event |

### beginInvoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo, System.AsyncCallback callback, Object state)
```


internal method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventInfo | [ProgressEventHandlerInfo](../../com.aspose.pdf/progresseventhandlerinfo) | internal object |
| callback | com.aspose.ms.System.AsyncCallback | internal object |
| state | java.lang.Object | internal object |

**Returns:**
com.aspose.ms.System.IAsyncResult - internal object
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```


internal method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | internal object |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




**Returns:**
boolean - boolean value
