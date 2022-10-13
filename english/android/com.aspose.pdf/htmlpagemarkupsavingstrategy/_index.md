---
title: HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for Java API Reference
description: Result of conversion can contain one or several HTML-pages  that also can reference external files like images or fonts You can assign to this property delegate created from custom method that implements processing of got HTML-pageHTML itself that was created during conversion.
type: docs
weight: 21
url: /java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends System.MulticastDelegate
```

Result of conversion can contain one or several HTML-pages ( that also can reference external files like images or fonts) You can assign to this property delegate created from custom method that implements processing of got HTML-page(HTML itself) that was created during conversion. In such case processing (like saving in stream or disk) can be done in that custom code . In such case All the necessary actions for saving of HTML page's markup must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it signals to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom saving code .
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlPageMarkupSavingStrategy()](#HtmlPageMarkupSavingStrategy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo)](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Invoked method |
| [beginInvoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Internal beginInvoke method |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Internal endInvoke method |
### HtmlPageMarkupSavingStrategy() {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```


### invoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo) {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
```
public abstract void invoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo)
```


Invoked method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlSavingInfo | [HtmlPageMarkupSavingInfo](../../com.aspose.pdf/htmlpagemarkupsavinginfo) | SaveOptions.ResourceSavingInfo object |

### beginInvoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(HtmlSaveOptions.HtmlPageMarkupSavingInfo htmlSavingInfo, System.AsyncCallback callback, Object state)
```


Internal beginInvoke method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlSavingInfo | [HtmlPageMarkupSavingInfo](../../com.aspose.pdf/htmlpagemarkupsavinginfo) | SaveOptions.ResourceSavingInfo object |
| callback | com.aspose.ms.System.AsyncCallback | AsyncCallback object |
| state | java.lang.Object | state object |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult object
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```


Internal endInvoke method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | IAsyncResult object |

