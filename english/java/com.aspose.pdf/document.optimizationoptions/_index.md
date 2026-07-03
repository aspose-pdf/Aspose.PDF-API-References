---
title: Document.OptimizationOptions
second_title: Aspose.PDF for Java API Reference
description: Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method. @deprecated This class is obsolete. Please.
type: docs
weight: 1110
url: /java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method. @deprecated This class is obsolete. Please use com.aspose.pdf.optimization.OptimizationOptions instead.

## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Deprecated. |

## Methods

| Method | Description |
| --- | --- |
| [all](#all--) | Creates optimization strategy will all options activated. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced. |
| [getResolution](#getResolution--) | Specifies new image dpi when CompressIamges flag is used. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced. |
| [setResolution](#setResolution-int-) | Specifies new image dpi when CompressIamges flag is used. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Deprecated.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Creates optimization strategy will all options activated.

**Returns:**
OptimizationOptions object.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced.

**Returns:**
image maximum dimension

### getResolution {#getResolution--}
```
public int getResolution()
```

Specifies new image dpi when CompressIamges flag is used.

**Returns:**
image resolution

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dimension |  | image maximum dimension |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Specifies new image dpi when CompressIamges flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpi |  | image resolution |
