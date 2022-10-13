---
title: Watermark
second_title: Aspose.PDF for Java API Reference
description: Represents a watermark of the page.
type: docs
weight: 318
url: /java/com.aspose.pdf/watermark/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Watermark extends Struct<Watermark>
```

Represents a watermark of the page.
## Constructors

| Constructor | Description |
| --- | --- |
| [Watermark()](#Watermark--) |  |
| [Watermark(System.Drawing.Image image, Rectangle rect)](#Watermark-com.aspose.ms.System.Drawing.Image-com.aspose.pdf.Rectangle-) | Initializes a watermark structure with an image and it's position on a page. |
| [Watermark(System.Drawing.Image image)](#Watermark-com.aspose.ms.System.Drawing.Image-) | Initializes a watermark structure with an image. |
## Methods

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | Gets an image of the watermark. |
| [getPosition()](#getPosition--) | Gets a position of the watermark's image on a page. |
| [getAvailable()](#getAvailable--) | Gets a flag the watermark is present. |
| [CloneTo(Watermark that)](#CloneTo-com.aspose.pdf.Watermark-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [equals(Watermark obj1, Watermark obj2)](#equals-com.aspose.pdf.Watermark-com.aspose.pdf.Watermark-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```


### Watermark(System.Drawing.Image image, Rectangle rect) {#Watermark-com.aspose.ms.System.Drawing.Image-com.aspose.pdf.Rectangle-}
```
public Watermark(System.Drawing.Image image, Rectangle rect)
```


Initializes a watermark structure with an image and it's position on a page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.ms.System.Drawing.Image |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### Watermark(System.Drawing.Image image) {#Watermark-com.aspose.ms.System.Drawing.Image-}
```
public Watermark(System.Drawing.Image image)
```


Initializes a watermark structure with an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.ms.System.Drawing.Image |  |

### getImage() {#getImage--}
```
public System.Drawing.Image getImage()
```


Gets an image of the watermark.

**Returns:**
[Image](../../com.aspose.ms.system.drawing/image)
### getPosition() {#getPosition--}
```
public Rectangle getPosition()
```


Gets a position of the watermark's image on a page.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### getAvailable() {#getAvailable--}
```
public boolean getAvailable()
```


Gets a flag the watermark is present.

**Returns:**
boolean
### CloneTo(Watermark that) {#CloneTo-com.aspose.pdf.Watermark-}
```
public void CloneTo(Watermark that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Watermark](../../com.aspose.pdf/watermark) |  |

### Clone() {#Clone--}
```
public Watermark Clone()
```




**Returns:**
[Watermark](../../com.aspose.pdf/watermark)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### equals(Watermark obj1, Watermark obj2) {#equals-com.aspose.pdf.Watermark-com.aspose.pdf.Watermark-}
```
public static boolean equals(Watermark obj1, Watermark obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Watermark](../../com.aspose.pdf/watermark) |  |
| obj2 | [Watermark](../../com.aspose.pdf/watermark) |  |

**Returns:**
boolean
