---
title: Redaction
second_title: Aspose.PDF for Java API Reference
description: For internal usage only
type: docs
weight: 301
url: /java/com.aspose.pdf/redaction/
---
**Inheritance:**
java.lang.Object
```
public class Redaction
```

For internal usage only
## Constructors

| Constructor | Description |
| --- | --- |
| [Redaction()](#Redaction--) |  |
## Methods

| Method | Description |
| --- | --- |
| [_RedactText(Page page, Rectangle rect)](#-RedactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getRedactionAppearance(Rectangle rect, Color color)](#getRedactionAppearance-com.aspose.pdf.Rectangle-java.awt.Color-) | get Redaction Appearance |
| [getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color)](#getRedactionAppearanceInternal-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-) | For Internal Usage only get Redaction Appearance |
| [getredactArea(Page page, Rectangle rect, Color color)](#getredactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | get redact Area |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [redactAnnotations(Page page, Rectangle rect)](#redactAnnotations-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Removes Annotation which is in required rectangle |
| [redactArea(Page page, Rectangle rect, Color color)](#redactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | For Internal Usage only get redact Area |
| [redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea)](#redactAreaInternal-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-boolean-) |  |
| [redactImages(Page page, Rectangle rect, Color color)](#redactImages-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | Removes images (or redacts contents of the image is image is partially covered by rectangle) |
| [redactText(Page page, Rectangle rect)](#redactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Removes text which is in requried rectangle |
| [redactText(XForm form, Rectangle rect)](#redactText-com.aspose.pdf.XForm-com.aspose.pdf.Rectangle-) | Removes text which is in requried rectangle |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Redaction() {#Redaction--}
```
public Redaction()
```


### _RedactText(Page page, Rectangle rect) {#-RedactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void _RedactText(Page page, Rectangle rect)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

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
### getRedactionAppearance(Rectangle rect, Color color) {#getRedactionAppearance-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static List<Operator> getRedactionAppearance(Rectangle rect, Color color)
```


get Redaction Appearance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |
| color | java.awt.Color | Color object |

**Returns:**
java.util.List<com.aspose.pdf.Operator> -  List object 
### getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color) {#getRedactionAppearanceInternal-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-}
```
public static System.Collections.Generic.List<Operator> getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color)
```


For Internal Usage only get Redaction Appearance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |
| color | com.aspose.ms.System.Drawing.Color | Color object |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> -  List object 
### getredactArea(Page page, Rectangle rect, Color color) {#getredactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void getredactArea(Page page, Rectangle rect, Color color)
```


get redact Area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |
| color | java.awt.Color | Color object |

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




### redactAnnotations(Page page, Rectangle rect) {#redactAnnotations-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void redactAnnotations(Page page, Rectangle rect)
```


Removes Annotation which is in required rectangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### redactArea(Page page, Rectangle rect, Color color) {#redactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void redactArea(Page page, Rectangle rect, Color color)
```


For Internal Usage only get redact Area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |
| color | java.awt.Color | Color object |

### redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea) {#redactAreaInternal-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-boolean-}
```
public static void redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |
| color | com.aspose.ms.System.Drawing.Color |  |
| exactArea | boolean |  |

### redactImages(Page page, Rectangle rect, Color color) {#redactImages-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void redactImages(Page page, Rectangle rect, Color color)
```


Removes images (or redacts contents of the image is image is partially covered by rectangle)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |
| color | java.awt.Color | Color object |

### redactText(Page page, Rectangle rect) {#redactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void redactText(Page page, Rectangle rect)
```


Removes text which is in requried rectangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### redactText(XForm form, Rectangle rect) {#redactText-com.aspose.pdf.XForm-com.aspose.pdf.Rectangle-}
```
public static void redactText(XForm form, Rectangle rect)
```


Removes text which is in requried rectangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | XForm object |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

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

