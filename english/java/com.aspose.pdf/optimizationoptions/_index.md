---
title: Document.OptimizationOptions
second_title: Aspose.PDF for Java API Reference
description: Class which describes document optimization algorithm.
type: docs
weight: 10
url: /java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.optimization.OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions)
```
public static class Document.OptimizationOptions extends OptimizationOptions
```

Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.
## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizationOptions()](#OptimizationOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [all()](#all--) | Creates optimization strategy will all options activated. |
| [getResolution()](#getResolution--) | Specifies new image dpi when CompressIamges flag is used. |
| [setResolution(int dpi)](#setResolution-int-) | Specifies new image dpi when CompressIamges flag is used. |
| [getMaximumImageDimension()](#getMaximumImageDimension--) | Specifies maximum image dimension. |
| [setMaximumImageDimension(int dimension)](#setMaximumImageDimension-int-) | Specifies maximum image dimension. |
### OptimizationOptions() {#OptimizationOptions--}
```
public OptimizationOptions()
```


### all() {#all--}
```
public static Document.OptimizationOptions all()
```


Creates optimization strategy will all options activated.

**Returns:**
[OptimizationOptions](../../com.aspose.pdf/optimizationoptions) - OptimizationOptions object.
### getResolution() {#getResolution--}
```
public int getResolution()
```


Specifies new image dpi when CompressIamges flag is used.

**Returns:**
int - image resolution
### setResolution(int dpi) {#setResolution-int-}
```
public void setResolution(int dpi)
```


Specifies new image dpi when CompressIamges flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpi | int | image resolution |

### getMaximumImageDimension() {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```


Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced.

**Returns:**
int - image maximum dimension
### setMaximumImageDimension(int dimension) {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```


Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dimension | int | image maximum dimension |

