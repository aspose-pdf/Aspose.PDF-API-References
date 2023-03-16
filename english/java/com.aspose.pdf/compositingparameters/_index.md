---
title: CompositingParameters
second_title: Aspose.PDF for Java API Reference
description: Represents an object containing graphics compositing parameters of current graphics state.
type: docs
weight: 72
url: /java/com.aspose.pdf/compositingparameters/
---
**Inheritance:**
java.lang.Object
```
public final class CompositingParameters
```

Represents an object containing graphics compositing parameters of current graphics state.
## Constructors

| Constructor | Description |
| --- | --- |
| [CompositingParameters(int blendMode)](#CompositingParameters-int-) | Initializes new instance of the  CompositingParameters  object. |
| [CompositingParameters(int blendMode, int filterType)](#CompositingParameters-int-int-) | Initializes new instance of the  CompositingParameters  object. |
| [CompositingParameters(int blendMode, int filterType, boolean isMasked)](#CompositingParameters-int-int-boolean-) | Initializes new instance of the  CompositingParameters  object. |
## Methods

| Method | Description |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Gets blend mode of current graphics state. |
| [getFilterType()](#getFilterType--) | Gets the image filter type. |
| [isMasked()](#isMasked--) | Gets the mask flag. |
### CompositingParameters(int blendMode) {#CompositingParameters-int-}
```
public CompositingParameters(int blendMode)
```


Initializes new instance of the  CompositingParameters  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| blendMode | int | Blend mode of current graphics state. |

### CompositingParameters(int blendMode, int filterType) {#CompositingParameters-int-int-}
```
public CompositingParameters(int blendMode, int filterType)
```


Initializes new instance of the  CompositingParameters  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| blendMode | int | Blend mode of current graphics state. |
| filterType | int | The image filter type. |

### CompositingParameters(int blendMode, int filterType, boolean isMasked) {#CompositingParameters-int-int-boolean-}
```
public CompositingParameters(int blendMode, int filterType, boolean isMasked)
```


Initializes new instance of the  CompositingParameters  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| blendMode | int | Blend mode of current graphics state. |
| filterType | int | The image filter type. |
| isMasked | boolean | The adding mask flag. |

### getBlendMode() {#getBlendMode--}
```
public int getBlendMode()
```


Gets blend mode of current graphics state.

**Returns:**
int - BlendMode element
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Gets the image filter type.

**Returns:**
int - ImageFilterType element
### isMasked() {#isMasked--}
```
public boolean isMasked()
```


Gets the mask flag.

**Returns:**
boolean - boolean value
