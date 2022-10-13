---
title: Page.BeforePageGenerate
second_title: Aspose.PDF for Java API Reference
description: Procedure for customize header and footer.
type: docs
weight: 10
url: /java/com.aspose.pdf/page.beforepagegenerate/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Page.BeforePageGenerate extends System.MulticastDelegate
```

Procedure for customize header and footer.
## Constructors

| Constructor | Description |
| --- | --- |
| [BeforePageGenerate()](#BeforePageGenerate--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Page page)](#invoke-com.aspose.pdf.Page-) |  |
| [beginInvoke(Page page, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.pdf.Page-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### BeforePageGenerate() {#BeforePageGenerate--}
```
public BeforePageGenerate()
```


### invoke(Page page) {#invoke-com.aspose.pdf.Page-}
```
public abstract void invoke(Page page)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |

### beginInvoke(Page page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.pdf.Page-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Page page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
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

