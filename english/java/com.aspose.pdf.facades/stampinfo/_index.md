---
title: StampInfo
second_title: Aspose.PDF for Java API Reference
description: Class representing stamp information.
type: docs
weight: 60
url: /java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object
```
public final class StampInfo
```

Class representing stamp information.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getForm()](#getForm--) | Gets XForm of the stamp. |
| [getImage()](#getImage--) | Gets image of stamp. |
| [getImageInternal()](#getImageInternal--) | Gets image of stamp. |
| [getIndexOnPage()](#getIndexOnPage--) | Gets stamp index on the page. |
| [getRectangle()](#getRectangle--) | Gets rectangle where stamp is placed. |
| [getStampId()](#getStampId--) | Gets identifier of the stamp. |
| [getStampType()](#getStampType--) | Gets stamp type (image / form). |
| [getText()](#getText--) | Gets text in the stamp. |
| [getVisible()](#getVisible--) | Gets visibility of stamp. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets XForm of the stamp.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### getImage() {#getImage--}
```
public BufferedImage getImage()
```


Gets image of stamp. May be null if stamp does not contain images (for example for text stamp).

**Returns:**
java.awt.image.BufferedImage - BufferedImage object
### getImageInternal() {#getImageInternal--}
```
public System.Drawing.Image getImageInternal()
```


Gets image of stamp. May be null if stamp does not contain images (for example for text stamp).

**Returns:**
[Image](../../com.aspose.ms.system.drawing/image) - Image object
### getIndexOnPage() {#getIndexOnPage--}
```
public int getIndexOnPage()
```


Gets stamp index on the page.

**Returns:**
int - int value
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle where stamp is placed.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle element
### getStampId() {#getStampId--}
```
public int getStampId()
```


Gets identifier of the stamp.

**Returns:**
int - int value
### getStampType() {#getStampType--}
```
public int getStampType()
```


Gets stamp type (image / form).

**Returns:**
int - StampType element
### getText() {#getText--}
```
public String getText()
```


Gets text in the stamp.

**Returns:**
java.lang.String - String value
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Gets visibility of stamp. If false then stamp is hidden (with HideStampById). Hidden stamp may be restored by ShowStampById.

**Returns:**
boolean - boolean value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

