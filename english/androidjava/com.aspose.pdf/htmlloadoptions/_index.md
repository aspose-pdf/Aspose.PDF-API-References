---
title: HtmlLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing html file into pdf document.
type: docs
weight: 134
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
## Fields

| Field | Description |
| --- | --- |
| [CustomLoaderOfExternalResources](#CustomLoaderOfExternalResources) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. |
## Methods

| Method | Description |
| --- | --- |
| [getInputEncoding()](#getInputEncoding--) | Gets the attribute specifying the encoding used for this document at the time of the parsing. |
| [setInputEncoding(String value)](#setInputEncoding-java.lang.String-) | Sets the attribute specifying the encoding used for this document at the time of the parsing. |
| [getBasePath()](#getBasePath--) | The base path/url for the html file. |
| [getPageInfo()](#getPageInfo--) | Gets document page info |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets document page info |
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

### CustomLoaderOfExternalResources {#CustomLoaderOfExternalResources}
```
public LoadOptions.ResourceLoadingStrategy CustomLoaderOfExternalResources
```


Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloud direct access to referenced files impossible: in such case some customer code put into special method should be used, and delegate that refers that method should be assigned to this attribute.

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

