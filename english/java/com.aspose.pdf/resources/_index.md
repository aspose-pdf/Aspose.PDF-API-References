---
title: Resources
second_title: Aspose.PDF for Java API Reference
description: Class representing page resources.
type: docs
weight: 310
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFonts()](#getFonts--) | Gets  Fonts  resources collection |
| [getFonts(boolean createIfAbsent)](#getFonts-boolean-) | Returns fonts collection. |
| [getForms()](#getForms--) | Gets  Forms  forms collection |
| [getImages()](#getImages--) | Gets  Images  images collection |
| [getResourcesFor(Form form)](#getResourcesFor-com.aspose.pdf.Form-) | Gets resources for |
| [hashCode()](#hashCode--) |  |
| [isCommonResource()](#isCommonResource--) | True if this resources are common i.e. are shared for several pages (placed in pages dictionary or in every page as object reference) Manipulation with common resources must be performed very carefully for example deleting object form common resources in one page may cause errors on other pages if deleted object was used for other pages. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResourceDictionary(IResourceDictionary resourceDictionary)](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | For internal usage only! |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearImagesCache() {#clearImagesCache--}
```
public final void clearImagesCache()
```




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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Gets  Fonts  resources collection

**Returns:**
[FontCollection](../../com.aspose.pdf/fontcollection) - FontCollection object
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCommonResource() {#isCommonResource--}
```
public boolean isCommonResource()
```


True if this resources are common i.e. are shared for several pages (placed in pages dictionary or in every page as object reference) Manipulation with common resources must be performed very carefully for example deleting object form common resources in one page may cause errors on other pages if deleted object was used for other pages.

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




### setResourceDictionary(IResourceDictionary resourceDictionary) {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
```
public void setResourceDictionary(IResourceDictionary resourceDictionary)
```


For internal usage only!

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceDictionary | [IResourceDictionary](../../com.aspose.pdf.engine.commondata.pagecontent/iresourcedictionary) | inernal instance |

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

