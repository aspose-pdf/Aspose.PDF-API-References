---
title: MemoryExtender
second_title: Aspose.PDF for Java API Reference
description: Represents MemoryExtender class Using large files on a system with limited heap memory can be enabled to use disk space as a temporary swap memory.
type: docs
weight: 219
url: /java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object
```
public class MemoryExtender
```

Represents MemoryExtender class Using large files on a system with limited heap memory, can be enabled to use disk space as a temporary swap memory.
## Constructors

| Constructor | Description |
| --- | --- |
| [MemoryExtender()](#MemoryExtender--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isSwapEnabled()](#isSwapEnabled--) | Is enabled to use disk space as a temporary swap memory. |
| [isOptimizedMemoryStreamByDefault()](#isOptimizedMemoryStreamByDefault--) | Is enabled to use OptimizedMemoryStream as default memory storage. |
| [isOptimizedMemoryStreamByDefault(boolean value)](#isOptimizedMemoryStreamByDefault-boolean-) | Is enabled to use OptimizedMemoryStream as default memory storage. |
| [setSwapEnabled(boolean value)](#setSwapEnabled-boolean-) | Set flag whether disk space is enabled to use as a temporary swap memory. |
| [isSkipHeavyContentEnabled()](#isSkipHeavyContentEnabled--) | Is enabled to skip objects with high memory consumption in rendering with lack of heap memory. |
| [setSkipHeavyContentEnabled(boolean value)](#setSkipHeavyContentEnabled-boolean-) | Set flag to enable to skip objects with high memory consumption in rendering with lack of heap memory. |
| [getElementRenderingTimeout()](#getElementRenderingTimeout--) | The maximum time for rendering single element used in page to image conversion. |
| [setElementRenderingTimeout(int value)](#setElementRenderingTimeout-int-) | The maximum time for rendering single element used in page to image conversion. |
| [getCallBackPageImage()](#getCallBackPageImage--) | Get the custom cache analyzer. |
| [setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_)](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Apply the new custom cache analyzer. |
| [isEnabledMultiPageImageCache()](#isEnabledMultiPageImageCache--) | Get the status for EnabledMultiPageImageCache field |
| [setEnableMultiPageCache(boolean enableMultiPageImageCache_)](#setEnableMultiPageCache-boolean-) | Set the new status for EnabledMultiPageImageCache field |
### MemoryExtender() {#MemoryExtender--}
```
public MemoryExtender()
```


### isSwapEnabled() {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```


Is enabled to use disk space as a temporary swap memory. Default value is FALSE

**Returns:**
boolean - boolean value
### isOptimizedMemoryStreamByDefault() {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```


Is enabled to use OptimizedMemoryStream as default memory storage. Required for work with large documents over 2 Gb. Default value is FALSE

**Returns:**
boolean - boolean value
### isOptimizedMemoryStreamByDefault(boolean value) {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```


Is enabled to use OptimizedMemoryStream as default memory storage. Required for work with large documents over 2 Gb. Default value is FALSE

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSwapEnabled(boolean value) {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```


Set flag whether disk space is enabled to use as a temporary swap memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isSkipHeavyContentEnabled() {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```


Is enabled to skip objects with high memory consumption in rendering with lack of heap memory. Default value is FALSE

**Returns:**
boolean - boolean value
### setSkipHeavyContentEnabled(boolean value) {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```


Set flag to enable to skip objects with high memory consumption in rendering with lack of heap memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getElementRenderingTimeout() {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```


The maximum time for rendering single element used in page to image conversion. Default value 10000 milliseconds. Used only when isSkipHeavyContentEnabled() == true

**Returns:**
int - int value Number of milliseconds
### setElementRenderingTimeout(int value) {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```


The maximum time for rendering single element used in page to image conversion. Default value 10000 milliseconds Used only when isSkipHeavyContentEnabled() == true

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value Number of milliseconds |

### getCallBackPageImage() {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```


Get the custom cache analyzer.

**Returns:**
[CallBackPageImage](../../com.aspose.pdf/callbackpageimage) - CallBackPageImage object
### setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_) {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
```
public static void setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_)
```


Apply the new custom cache analyzer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callBackPageImage_ | [CallBackPageImage](../../com.aspose.pdf/callbackpageimage) | CallBackPageImage object |

### isEnabledMultiPageImageCache() {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```


Get the status for EnabledMultiPageImageCache field

**Returns:**
boolean - boolean value
### setEnableMultiPageCache(boolean enableMultiPageImageCache_) {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```


Set the new status for EnabledMultiPageImageCache field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enableMultiPageImageCache_ | boolean | boolean value |

