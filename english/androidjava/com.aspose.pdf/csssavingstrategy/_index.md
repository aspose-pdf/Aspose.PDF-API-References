---
title: HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for Java API Reference
description: You can assign to this property custom strategy that implements processing or/and saving of one CSSs part that was created during conversion of PDF to HTML .
type: docs
weight: 12
url: /java/com.aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.CssSavingStrategy extends System.MulticastDelegate
```

You can assign to this property custom strategy that implements processing or/and saving of one CSS's part that was created during conversion of PDF to HTML . In such case processing (like saving to stream or disk) must be done in that custom code
## Constructors

| Constructor | Description |
| --- | --- |
| [CssSavingStrategy()](#CssSavingStrategy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(HtmlSaveOptions.CssSavingInfo partSavingInfo)](#invoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-) |  |
| [beginInvoke(HtmlSaveOptions.CssSavingInfo partSavingInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### CssSavingStrategy() {#CssSavingStrategy--}
```
public CssSavingStrategy()
```


### invoke(HtmlSaveOptions.CssSavingInfo partSavingInfo) {#invoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-}
```
public abstract void invoke(HtmlSaveOptions.CssSavingInfo partSavingInfo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| partSavingInfo | [CssSavingInfo](../../com.aspose.pdf/csssavinginfo) |  |

### beginInvoke(HtmlSaveOptions.CssSavingInfo partSavingInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(HtmlSaveOptions.CssSavingInfo partSavingInfo, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| partSavingInfo | [CssSavingInfo](../../com.aspose.pdf/csssavinginfo) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

