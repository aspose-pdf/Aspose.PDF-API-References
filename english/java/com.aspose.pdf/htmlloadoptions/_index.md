---
title: HtmlLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing html file into pdf document.
type: docs
weight: 158
url: /java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class HtmlLoadOptions extends LoadOptions
```

Represents options for loading/importing html file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlLoadOptions()](#HtmlLoadOptions--) | Creates load options for converting html into pdf document with empty base path. |
| [HtmlLoadOptions(String basePath)](#HtmlLoadOptions-java.lang.String-) | Creates load options for converting html into pdf document with defined base path. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | The base path/url for the html file. |
| [getClass()](#getClass--) |  |
| [getCustomLoaderOfExternalResources()](#getCustomLoaderOfExternalResources--) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. |
| [getHtmlMediaType()](#getHtmlMediaType--) | Gets or sets possible media types used during rendering. |
| [getInputEncoding()](#getInputEncoding--) | Gets the attribute specifying the encoding used for this document at the time of the parsing. |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getPageInfo()](#getPageInfo--) | Gets document page info |
| [getPageLayoutOption()](#getPageLayoutOption--) | Gets or sets layout option. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isEmbedFonts()](#isEmbedFonts--) | Gets or sets fonts embedding to result document |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Gets or sets rendering all document to single page |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. |
| [setEmbedFonts(boolean value)](#setEmbedFonts-boolean-) | Gets or sets fonts embedding to result document |
| [setHtmlMediaType(int value)](#setHtmlMediaType-int-) | Gets or sets possible media types used during rendering. |
| [setInputEncoding(String value)](#setInputEncoding-java.lang.String-) | Sets the attribute specifying the encoding used for this document at the time of the parsing. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets document page info |
| [setPageLayoutOption(int value)](#setPageLayoutOption-int-) | Gets or sets layout option. |
| [setRenderToSinglePage(boolean value)](#setRenderToSinglePage-boolean-) | Gets or sets rendering all document to single page |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlLoadOptions() {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```


Creates load options for converting html into pdf document with empty base path.

### HtmlLoadOptions(String basePath) {#HtmlLoadOptions-java.lang.String-}
```
public HtmlLoadOptions(String basePath)
```


Creates load options for converting html into pdf document with defined base path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| basePath | java.lang.String | The base path/url for the html file. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


The base path/url for the html file.

**Returns:**
java.lang.String - String value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomLoaderOfExternalResources() {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```


Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloud direct access to referenced files impossible: in such case some customer code put into special method should be used, and delegate that refers that method should be assigned to this attribute.

**Returns:**
[ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) - ResourceLoadingStrategy instance
### getHtmlMediaType() {#getHtmlMediaType--}
```
public int getHtmlMediaType()
```


Gets or sets possible media types used during rendering.

**Returns:**
int - HtmlMediaType element
### getInputEncoding() {#getInputEncoding--}
```
public String getInputEncoding()
```


Gets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute.

**Returns:**
java.lang.String - String value
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets document page info

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - page info
### getPageLayoutOption() {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```


Gets or sets layout option.

**Returns:**
int - HtmlPageLayoutOption element
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmbedFonts() {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```


Gets or sets fonts embedding to result document

**Returns:**
boolean - boolean value
### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```


Gets or sets rendering all document to single page

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources) {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
```
public void setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)
```


Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloud direct access to referenced files impossible: in such case some customer code put into special method should be used, and delegate that refers that method should be assigned to this attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customLoaderOfExternalResources | [ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) | ResourceLoadingStrategy instance |

### setEmbedFonts(boolean value) {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```


Gets or sets fonts embedding to result document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHtmlMediaType(int value) {#setHtmlMediaType-int-}
```
public void setHtmlMediaType(int value)
```


Gets or sets possible media types used during rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HtmlMediaType element |

### setInputEncoding(String value) {#setInputEncoding-java.lang.String-}
```
public void setInputEncoding(String value)
```


Sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets document page info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | page info |

### setPageLayoutOption(int value) {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```


Gets or sets layout option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HtmlPageLayoutOption element |

### setRenderToSinglePage(boolean value) {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```


Gets or sets rendering all document to single page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

