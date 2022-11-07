---
title: Resources
second_title: Aspose.PDF for Java API Reference
description: Class representing page resources.
type: docs
weight: 251
url: /java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object
```
public final class Resources
```

Class representing page resources.
## Fields

| Field | Description |
| --- | --- |
| [_ResourceDictionary](#-ResourceDictionary) |  |
## Methods

| Method | Description |
| --- | --- |
| [getEngineDict()](#getEngineDict--) |  |
| [getForms()](#getForms--) | Gets  Forms  forms collection |
| [getImages()](#getImages--) | Gets  Images  images collection |
| [getFonts(boolean createIfAbsent)](#getFonts-boolean-) | Returns fonts collection. |
| [getFonts()](#getFonts--) | Gets  Fonts  resources collection |
| [create(IDocument doc, IResourceDictionary res)](#create-com.aspose.pdf.IDocument-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) |  |
| [getResourcesFor(Form form)](#getResourcesFor-com.aspose.pdf.Form-) |  |
| [isCommonResource()](#isCommonResource--) | True if this resources are common i.e. are shared for several pages (placed in pages dictionary or in every page as object reference) Manipulation with common resources must be performed very carefully for example deleting object form common resources in one page may cause errors on other pages if deleted object was used for other pages. |
### _ResourceDictionary {#-ResourceDictionary}
```
public IResourceDictionary _ResourceDictionary
```


### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```




**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getForms() {#getForms--}
```
public XFormCollection getForms()
```


Gets  Forms  forms collection

**Returns:**
[XFormCollection](../../com.aspose.pdf/xformcollection)
### getImages() {#getImages--}
```
public XImageCollection getImages()
```


Gets  Images  images collection

**Returns:**
[XImageCollection](../../com.aspose.pdf/ximagecollection)
### getFonts(boolean createIfAbsent) {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```


Returns fonts collection. If resources don't contain fonts entry it will be created in depends of CreateIfAbsent flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createIfAbsent | boolean | If this flag is true then fonts will be created if this entry is absent. |

**Returns:**
[FontCollection](../../com.aspose.pdf/fontcollection) - Fonts collection.
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Gets  Fonts  resources collection

**Returns:**
[FontCollection](../../com.aspose.pdf/fontcollection)
### create(IDocument doc, IResourceDictionary res) {#create-com.aspose.pdf.IDocument-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
```
public static Resources create(IDocument doc, IResourceDictionary res)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) |  |
| res | [IResourceDictionary](../../com.aspose.pdf.engine.commondata.pagecontent/iresourcedictionary) |  |

**Returns:**
[Resources](../../com.aspose.pdf/resources)
### getResourcesFor(Form form) {#getResourcesFor-com.aspose.pdf.Form-}
```
public static Resources getResourcesFor(Form form)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [Form](../../com.aspose.pdf/form) |  |

**Returns:**
[Resources](../../com.aspose.pdf/resources)
### isCommonResource() {#isCommonResource--}
```
public boolean isCommonResource()
```


True if this resources are common i.e. are shared for several pages (placed in pages dictionary or in every page as object reference) Manipulation with common resources must be performed very carefully for example deleting object form common resources in one page may cause errors on other pages if deleted object was used for other pages.

**Returns:**
boolean
