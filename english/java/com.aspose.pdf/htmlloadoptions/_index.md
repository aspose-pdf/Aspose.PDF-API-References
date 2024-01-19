---
title: HtmlLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing html file into pdf document.
type: docs
weight: 157
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
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Gets or sets rendering all document to single page |
| [setRenderToSinglePage(boolean value)](#setRenderToSinglePage-boolean-) | Gets or sets rendering all document to single page |
| [isEmbedFonts()](#isEmbedFonts--) | Gets or sets fonts embedding to result document |
| [setEmbedFonts(boolean value)](#setEmbedFonts-boolean-) | Gets or sets fonts embedding to result document |
| [getPageLayoutOption()](#getPageLayoutOption--) | Gets or sets layout option. |
| [setPageLayoutOption(int value)](#setPageLayoutOption-int-) | Gets or sets layout option. |
| [getHtmlMediaType()](#getHtmlMediaType--) | Gets or sets possible media types used during rendering. |
| [setHtmlMediaType(int value)](#setHtmlMediaType-int-) | Gets or sets possible media types used during rendering. |
| [getInputEncoding()](#getInputEncoding--) | Gets the attribute specifying the encoding used for this document at the time of the parsing. |
| [setInputEncoding(String value)](#setInputEncoding-java.lang.String-) | Sets the attribute specifying the encoding used for this document at the time of the parsing. |
| [getBasePath()](#getBasePath--) | The base path/url for the html file. |
| [getPageInfo()](#getPageInfo--) | Gets document page info |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets document page info |
| [getCustomLoaderOfExternalResources()](#getCustomLoaderOfExternalResources--) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. |
| [setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. |
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

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```


Gets or sets rendering all document to single page

**Returns:**
boolean - boolean value
### setRenderToSinglePage(boolean value) {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```


Gets or sets rendering all document to single page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isEmbedFonts() {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```


Gets or sets fonts embedding to result document

**Returns:**
boolean - boolean value
### setEmbedFonts(boolean value) {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```


Gets or sets fonts embedding to result document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getPageLayoutOption() {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```


Gets or sets layout option.

**Returns:**
int - HtmlPageLayoutOption element
### setPageLayoutOption(int value) {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```


Gets or sets layout option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HtmlPageLayoutOption element |

### getHtmlMediaType() {#getHtmlMediaType--}
```
public int getHtmlMediaType()
```


Gets or sets possible media types used during rendering.

**Returns:**
int - HtmlMediaType element
### setHtmlMediaType(int value) {#setHtmlMediaType-int-}
```
public void setHtmlMediaType(int value)
```


Gets or sets possible media types used during rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HtmlMediaType element |

### getInputEncoding() {#getInputEncoding--}
```
public String getInputEncoding()
```


Gets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute.

**Returns:**
java.lang.String - String value
### setInputEncoding(String value) {#setInputEncoding-java.lang.String-}
```
public void setInputEncoding(String value)
```


Sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


The base path/url for the html file.

**Returns:**
java.lang.String - String value
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets document page info

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - page info
### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets document page info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | page info |

### getCustomLoaderOfExternalResources() {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```


Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloud direct access to referenced files impossible: in such case some customer code put into special method should be used, and delegate that refers that method should be assigned to this attribute.

**Returns:**
[ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) - ResourceLoadingStrategy instance
### setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources) {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
```
public void setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)
```


Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloud direct access to referenced files impossible: in such case some customer code put into special method should be used, and delegate that refers that method should be assigned to this attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customLoaderOfExternalResources | [ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) | ResourceLoadingStrategy instance |

