---
title: ImageStamp
second_title: Aspose.PDF for Java API Reference
description: Represents a graphic stamp.
type: docs
weight: 2360
url: /java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Represents a graphic stamp.

## Constructors

| Constructor | Description |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Initializes a new instance of the {@code ImageStamp} class. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Creates image stamp by image in the specified file. |

## Methods

| Method | Description |
| --- | --- |
| [close](#close--) | Closes this instance |
| [getAlternativeText](#getAlternativeText--) | Gets Alternative Text for image stamp. |
| [getHeight](#getHeight--) | Gets image height. Setting this image allows to scale image vertically. |
| [getImage](#getImage--) | Gets image stream used for stamping. |
| [getQuality](#getQuality--) | Gets quality of image stamp in percent. Valid values are 0..100%. |
| [getWidth](#getWidth--) | Gets image width. Setting this property allos to scal image horizontally. |
| [getXIndent](#getXIndent--) | Gets and sets horizontal stamp coordinate, starting from the left. |
| [getYIndent](#getYIndent--) | Gets and sets vertical stamp coordinate, starting from the bottom. |
| [put](#put-com.aspose.pdf.Page-) | Adds graphic stamp on the page. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Sets Alternative Text for image stamp. |
| [setHeight](#setHeight-double-) | Sets image height. Setting this image allows to scale image vertically. |
| [setQuality](#setQuality-int-) | Sets quality of image stamp in percent. Valid values are 0..100%. |
| [setWidth](#setWidth-double-) | Sets image width. Setting this property allos to scal image horizontally. |
| [setXIndent](#setXIndent-double-) | Gets and sets horizontal stamp coordinate, starting from the left. |
| [setYIndent](#setYIndent-double-) | Gets and sets vertical stamp coordinate, starting from the bottom. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Initializes a new instance of the {@code ImageStamp} class.

### ImageStamp {#ImageStamp-java.lang.String-}
Creates image stamp by image in the specified file.

### close {#close--}
```
public void close()
```

Closes this instance

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Gets Alternative Text for image stamp.

**Returns:**
String value

### getHeight {#getHeight--}
```
public double getHeight()
```

Gets image height. Setting this image allows to scale image vertically.

**Returns:**
double value

### getImage {#getImage--}
```
public InputStream getImage()
```

Gets image stream used for stamping.

**Returns:**
InputStream object

### getQuality {#getQuality--}
```
public int getQuality()
```

Gets quality of image stamp in percent. Valid values are 0..100%.

**Returns:**
int value

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets image width. Setting this property allos to scal image horizontally.

**Returns:**
double value

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Gets and sets horizontal stamp coordinate, starting from the left.

**Returns:**
double value

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Gets and sets vertical stamp coordinate, starting from the bottom.

**Returns:**
double value

### put {#put-com.aspose.pdf.Page-}
Adds graphic stamp on the page.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Sets Alternative Text for image stamp.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sets image height. Setting this image allows to scale image vertically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Sets quality of image stamp in percent. Valid values are 0..100%.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets image width. Setting this property allos to scal image horizontally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Gets and sets horizontal stamp coordinate, starting from the left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Gets and sets vertical stamp coordinate, starting from the bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |
