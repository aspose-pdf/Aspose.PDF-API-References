---
title: Group
second_title: Aspose.PDF for Java API Reference
description: A group attributes class specifying the attributes of the pageu2019s page group for use in the transparent imaging model.
type: docs
weight: 148
url: /java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object
```
public final class Group
```

A group attributes class specifying the attributes of the page\\u2019s page group for use in the transparent imaging model.
## Constructors

| Constructor | Description |
| --- | --- |
| [Group(Page page)](#Group-com.aspose.pdf.Page-) | The constructor. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Gets ColorSpace |
| [hashCode()](#hashCode--) |  |
| [isKnockout()](#isKnockout--) | for Internal usage only |
| [isTransparency()](#isTransparency--) | for Internal usage only |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorSpace(int value)](#setColorSpace-int-) | The group color space. |
| [setKnockout(int value)](#setKnockout-int-) | If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Group(Page page) {#Group-com.aspose.pdf.Page-}
```
public Group(Page page)
```


The constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf page object. |

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
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Gets ColorSpace

**Returns:**
int - ColorSpace value.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isKnockout() {#isKnockout--}
```
public int isKnockout()
```


for Internal usage only

If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects.

**Returns:**
int - ExtendedBoolean element
### isTransparency() {#isTransparency--}
```
public boolean isTransparency()
```


for Internal usage only

returns The group transparency flag.

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




### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


The group color space.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColorSpace value. |

### setKnockout(int value) {#setKnockout-int-}
```
public void setKnockout(int value)
```


If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ExtendedBoolean element |

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

