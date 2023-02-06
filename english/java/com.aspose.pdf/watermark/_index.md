---
title: Watermark
second_title: Aspose.PDF for Java API Reference
description: Represents a watermark of the page.
type: docs
weight: 405
url: /java/com.aspose.pdf/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Represents a watermark of the page.
## Constructors

| Constructor | Description |
| --- | --- |
| [Watermark(BufferedImage nativeImage, Rectangle rect)](#Watermark-java.awt.image.BufferedImage-com.aspose.pdf.Rectangle-) | Initializes a watermark object with an image and it's position on a page. |
| [Watermark(BufferedImage nativeImage)](#Watermark-java.awt.image.BufferedImage-) | Initializes a watermark structure with an image. |
## Methods

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | Gets an image of the watermark. |
| [getPosition()](#getPosition--) | Gets a position of the watermark's image on a page. |
| [getAvailable()](#getAvailable--) | Gets a flag the watermark is present. |
### Watermark(BufferedImage nativeImage, Rectangle rect) {#Watermark-java.awt.image.BufferedImage-com.aspose.pdf.Rectangle-}
```
public Watermark(BufferedImage nativeImage, Rectangle rect)
```


Initializes a watermark object with an image and it's position on a page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nativeImage | java.awt.image.BufferedImage | image Image of the watermark. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Position of the watermark on the page. |

### Watermark(BufferedImage nativeImage) {#Watermark-java.awt.image.BufferedImage-}
```
public Watermark(BufferedImage nativeImage)
```


Initializes a watermark structure with an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nativeImage | java.awt.image.BufferedImage | image Image of the watermark. |

### getImage() {#getImage--}
```
public BufferedImage getImage()
```


Gets an image of the watermark.

**Returns:**
java.awt.image.BufferedImage - BufferedImage object
### getPosition() {#getPosition--}
```
public Rectangle getPosition()
```


Gets a position of the watermark's image on a page.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getAvailable() {#getAvailable--}
```
public boolean getAvailable()
```


Gets a flag the watermark is present.

**Returns:**
boolean - boolean value
