---
title: Resources
second_title: Aspose.PDF for Java API Reference
description: Class representing page resources.
type: docs
weight: 313
url: /java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object
```
public final class Resources
```

Class representing page resources.
## Methods

| Method | Description |
| --- | --- |
| [clearImagesCache()](#clearImagesCache--) |  |
| [getForms()](#getForms--) | Gets  Forms  forms collection |
| [getImages()](#getImages--) | Gets  Images  images collection |
| [getFonts(boolean createIfAbsent)](#getFonts-boolean-) | Returns fonts collection. |
| [getFonts()](#getFonts--) | Gets  Fonts  resources collection |
| [getExtGStates()](#getExtGStates--) | Gets all ExGStates from resources. |
| [getResourcesFor(Form form)](#getResourcesFor-com.aspose.pdf.Form-) | Gets resources for |
| [isCommonResource()](#isCommonResource--) | True if this resources are common i.e. |
| [setResourceDictionary(IResourceDictionary resourceDictionary)](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | For internal usage only! |
### clearImagesCache() {#clearImagesCache--}
```
public final void clearImagesCache()
```




### getForms() {#getForms--}
```
public XFormCollection getForms()
```


Gets  Forms  forms collection

**Returns:**
[XFormCollection](../../com.aspose.pdf/xformcollection) - XFormCollection object
### getImages() {#getImages--}
```
public XImageCollection getImages()
```


Gets  Images  images collection

**Returns:**
[XImageCollection](../../com.aspose.pdf/ximagecollection) - XImageCollection object
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
[FontCollection](../../com.aspose.pdf/fontcollection) - FontCollection object
### getExtGStates() {#getExtGStates--}
```
public final System.Collections.Generic.Dictionary<String,Resources.ExtGStateValue> getExtGStates()
```


Gets all ExGStates from resources.

**Returns:**
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) - Returns dictionary with ExGStates names keys.
### getResourcesFor(Form form) {#getResourcesFor-com.aspose.pdf.Form-}
```
public static Resources getResourcesFor(Form form)
```


Gets resources for

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [Form](../../com.aspose.pdf/form) | Form object |

**Returns:**
[Resources](../../com.aspose.pdf/resources) - Resources object
### isCommonResource() {#isCommonResource--}
```
public boolean isCommonResource()
```


True if this resources are common i.e. are shared for several pages (placed in pages dictionary or in every page as object reference) Manipulation with common resources must be performed very carefully for example deleting object form common resources in one page may cause errors on other pages if deleted object was used for other pages.

**Returns:**
boolean - boolean value
### setResourceDictionary(IResourceDictionary resourceDictionary) {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
```
public void setResourceDictionary(IResourceDictionary resourceDictionary)
```


For internal usage only!

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceDictionary | [IResourceDictionary](../../com.aspose.pdf.engine.commondata.pagecontent/iresourcedictionary) | inernal instance |

