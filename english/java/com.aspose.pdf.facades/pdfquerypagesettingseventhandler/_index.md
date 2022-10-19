---
title: PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for Java API Reference
description: Represents the method that handles the QueryPageSettings event of a PrintDocument.
type: docs
weight: 52
url: /java/com.aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class PdfQueryPageSettingsEventHandler extends System.MulticastDelegate
```

Represents the method that handles the QueryPageSettings event of a PrintDocument.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfQueryPageSettingsEventHandler()](#PdfQueryPageSettingsEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, System.Drawing.Printing.QueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo)](#invoke-java.lang.Object-com.aspose.ms.System.Drawing.Printing.QueryPageSettingsEventArgs-com.aspose.pdf.facades.PdfPrintPageInfo-) | Represents the method that handles the QueryPageSettings event of a PrintDocument. |
| [beginInvoke(Object sender, System.Drawing.Printing.QueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.ms.System.Drawing.Printing.QueryPageSettingsEventArgs-com.aspose.pdf.facades.PdfPrintPageInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Internal method |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Internal method |
### PdfQueryPageSettingsEventHandler() {#PdfQueryPageSettingsEventHandler--}
```
public PdfQueryPageSettingsEventHandler()
```


### invoke(Object sender, System.Drawing.Printing.QueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo) {#invoke-java.lang.Object-com.aspose.ms.System.Drawing.Printing.QueryPageSettingsEventArgs-com.aspose.pdf.facades.PdfPrintPageInfo-}
```
public abstract void invoke(Object sender, System.Drawing.Printing.QueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo)
```


Represents the method that handles the QueryPageSettings event of a PrintDocument.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | The source of the event. |
| queryPageSettingsEventArgs | com.aspose.ms.System.Drawing.Printing.QueryPageSettingsEventArgs | A QueryPageSettingsEventArgs that contains the event data. |
| currentPageInfo | [PdfPrintPageInfo](../../com.aspose.pdf.facades/pdfprintpageinfo) | Currently printed page info. |

### beginInvoke(Object sender, System.Drawing.Printing.QueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.ms.System.Drawing.Printing.QueryPageSettingsEventArgs-com.aspose.pdf.facades.PdfPrintPageInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, System.Drawing.Printing.QueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo, System.AsyncCallback callback, Object state)
```


Internal method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | Internal object |
| queryPageSettingsEventArgs | com.aspose.ms.System.Drawing.Printing.QueryPageSettingsEventArgs | Internal object |
| currentPageInfo | [PdfPrintPageInfo](../../com.aspose.pdf.facades/pdfprintpageinfo) | Internal object |
| callback | com.aspose.ms.System.AsyncCallback | Internal object |
| state | java.lang.Object | Internal object |

**Returns:**
com.aspose.ms.System.IAsyncResult - Internal object
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```


Internal method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | Internal object |

