---
title: HtmlLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing html file into pdf document.
type: docs
weight: 1960
url: /java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Represents options for loading/importing html file into pdf document.

## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Creates load options for converting html into pdf document with empty base path. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Creates load options for converting html into pdf document with empty base path. |

## Methods

| Method | Description |
| --- | --- |
| [getBasePath](#getBasePath--) | The base path/url for the html file. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloud direct access to referenced files impossible: in such case some customer code put into special method should be used, and delegate that refers that method should be assigned to this attribute. |
| [getHtmlMediaType](#getHtmlMediaType--) | Gets or sets possible media types used during rendering. |
| [getInputEncoding](#getInputEncoding--) | Gets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute. |
| [getPageInfo](#getPageInfo--) | Gets document page info |
| [getPageLayoutOption](#getPageLayoutOption--) | Gets or sets layout option. |
| [isEmbedFonts](#isEmbedFonts--) | Gets or sets fonts embedding to result document |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Gets or sets the flag that specifies that @page rules defined in css will override values defined in PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Gets or sets rendering all document to single page |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Gets or sets fonts embedding to result document |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Gets or sets possible media types used during rendering. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets document page info |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Gets or sets layout option. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Gets or sets the flag that specifies that @page rules defined in css will override values defined in PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Gets or sets rendering all document to single page |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Creates load options for converting html into pdf document with empty base path.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Creates load options for converting html into pdf document with empty base path.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

The base path/url for the html file.

**Returns:**
String value

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloud direct access to referenced files impossible: in such case some customer code put into special method should be used, and delegate that refers that method should be assigned to this attribute.

**Returns:**
ResourceLoadingStrategy instance

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Gets or sets possible media types used during rendering.

**Returns:**
HtmlMediaType element

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Gets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute.

**Returns:**
String value

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Gets document page info

**Returns:**
page info

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Gets or sets layout option.

**Returns:**
HtmlPageLayoutOption element @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Gets or sets fonts embedding to result document

**Returns:**
boolean value

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Gets or sets the flag that specifies that @page rules defined in css will override values defined in PageInfo.

**Returns:**
boolean value

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Gets or sets rendering all document to single page

**Returns:**
boolean value

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Gets or sets fonts embedding to result document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Gets or sets possible media types used during rendering.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Sets document page info

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Gets or sets layout option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | HtmlPageLayoutOption element @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Gets or sets the flag that specifies that @page rules defined in css will override values defined in PageInfo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Gets or sets rendering all document to single page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
