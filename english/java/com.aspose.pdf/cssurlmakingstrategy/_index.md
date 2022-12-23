---
title: HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for Java API Reference
description: You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document.
type: docs
weight: 13
url: /java/com.aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.CssUrlMakingStrategy extends System.MulticastDelegate
```

You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document. F.e. if You want to make CSS referenced in HTML f.e. as "otherPage.ASPX?CssID=zjjkklj" Then such custom strategy must return "otherPage.ASPX?CssID=zjjkklj"
## Constructors

| Constructor | Description |
| --- | --- |
| [CssUrlMakingStrategy()](#CssUrlMakingStrategy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo)](#invoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-) |  |
| [beginInvoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### CssUrlMakingStrategy() {#CssUrlMakingStrategy--}
```
public CssUrlMakingStrategy()
```


### invoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo) {#invoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-}
```
public abstract String invoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cssUrlRequestInfo | [CssUrlRequestInfo](../../com.aspose.pdf/cssurlrequestinfo) |  |

**Returns:**
java.lang.String
### beginInvoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.CssUrlRequestInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(HtmlSaveOptions.CssUrlRequestInfo cssUrlRequestInfo, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cssUrlRequestInfo | [CssUrlRequestInfo](../../com.aspose.pdf/cssurlrequestinfo) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final String endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | IAsyncResult object |

**Returns:**
java.lang.String - String object
