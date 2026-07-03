---
title: Resources
linktitle: Resources
second_title: Aspose.PDF for Java API Reference
description: Class representing page resources.
type: docs
weight: 4220
url: /java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Class representing page resources.

## Methods

| Method | Description |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Clears cached data, frees memory etc. |
| [getExtGStates](#getExtGStates--) | Gets all ExGStates from resources. |
| [getFonts](#getFonts--) | Gets {@code Fonts} resources collection |
| [getFonts](#getFonts-boolean-) | Returns fonts collection. If resources don't contain fonts entry it will be created in depends of CreateIfAbsent flag. |
| [getForms](#getForms--) | Gets {@code Forms} forms collection |
| [getImages](#getImages--) | Gets {@code Images} images collection |
| [getResourceDictionary](#getResourceDictionary--) | Internal field |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Gets resources for |
| [isCommonResource](#isCommonResource--) | True if this resources are common i.e. are shared for several pages (placed in pages dictionary or in every page as object reference) Manipulation with common resources must be performed very carefully for example deleting object form common resources in one page may cause errors on other pages if deleted object was used for other pages. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | For internal usage only! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Clears cached data, frees memory etc.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Gets all ExGStates from resources.

**Returns:**
Returns dictionary with ExGStates names keys.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Gets {@code Fonts} resources collection

**Returns:**
FontCollection object

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Returns fonts collection. If resources don't contain fonts entry it will be created in depends of CreateIfAbsent flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createIfAbsent |  | If this flag is true then fonts will be created if this entry is absent. |

**Returns:**
Fonts collection.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Gets {@code Forms} forms collection

**Returns:**
XFormCollection object

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Gets {@code Images} images collection

**Returns:**
XImageCollection object

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Internal field

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Gets resources for

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

True if this resources are common i.e. are shared for several pages (placed in pages dictionary or in every page as object reference) Manipulation with common resources must be performed very carefully for example deleting object form common resources in one page may cause errors on other pages if deleted object was used for other pages.

**Returns:**
boolean value

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
For internal usage only!
