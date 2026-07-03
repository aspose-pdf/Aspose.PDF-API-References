---
title: MemoryExtender
second_title: Aspose.PDF for Java API Reference
description: Represents MemoryExtender class Using large files on a system with limited heap memory, can be enabled to use disk space as a temporary swap memory.
type: docs
weight: 3020
url: /java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Represents MemoryExtender class Using large files on a system with limited heap memory, can be enabled to use disk space as a temporary swap memory.

## Constructors

| Constructor | Description |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Get the custom cache analyzer. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | The maximum time for rendering single element used in page to image conversion. Default value 10000 milliseconds. Used only when isSkipHeavyContentEnabled() == true |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Get the status for EnabledMultiPageImageCache field |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | Is enabled to use OptimizedMemoryStream as default memory storage. Required for work with large documents over 2 Gb. Default value is FALSE |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | Is enabled to use OptimizedMemoryStream as default memory storage. Required for work with large documents over 2 Gb. Default value is FALSE |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Is enabled to skip objects with high memory consumption in rendering with lack of heap memory. Default value is FALSE |
| [isSwapEnabled](#isSwapEnabled--) | Is enabled to use disk space as a temporary swap memory. Default value is FALSE |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Gets a value indicating whether missing folders should be automatically created. <p>If set to {@code true}, Aspose methods that save by path will attempt to create the target folder structure if it does not already exist. <p>The default value is {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Apply the new custom cache analyzer. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | The maximum time for rendering single element used in page to image conversion. Default value 10000 milliseconds Used only when isSkipHeavyContentEnabled() == true |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Set the new status for EnabledMultiPageImageCache field |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Set flag to enable to skip objects with high memory consumption in rendering with lack of heap memory. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Set flag whether disk space is enabled to use as a temporary swap memory. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Sets a value indicating whether missing folders should be automatically created. <p>If set to {@code true}, Aspose methods that save by path will attempt to create the target folder structure if it does not already exist. <p>The default value is {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Get the custom cache analyzer.

**Returns:**
CallBackPageImage object

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

The maximum time for rendering single element used in page to image conversion. Default value 10000 milliseconds. Used only when isSkipHeavyContentEnabled() == true

**Returns:**
int value Number of milliseconds

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Get the status for EnabledMultiPageImageCache field

**Returns:**
boolean value

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

Is enabled to use OptimizedMemoryStream as default memory storage. Required for work with large documents over 2 Gb. Default value is FALSE

**Returns:**
boolean value

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

Is enabled to use OptimizedMemoryStream as default memory storage. Required for work with large documents over 2 Gb. Default value is FALSE

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Is enabled to skip objects with high memory consumption in rendering with lack of heap memory. Default value is FALSE

**Returns:**
boolean value

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Is enabled to use disk space as a temporary swap memory. Default value is FALSE

**Returns:**
boolean value

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Gets a value indicating whether missing folders should be automatically created. <p>If set to {@code true}, Aspose methods that save by path will attempt to create the target folder structure if it does not already exist. <p>The default value is {@code false}.

**Returns:**
boolean value

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Apply the new custom cache analyzer.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

The maximum time for rendering single element used in page to image conversion. Default value 10000 milliseconds Used only when isSkipHeavyContentEnabled() == true

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value Number of milliseconds |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Set the new status for EnabledMultiPageImageCache field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | boolean value |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Set flag to enable to skip objects with high memory consumption in rendering with lack of heap memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Set flag whether disk space is enabled to use as a temporary swap memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Sets a value indicating whether missing folders should be automatically created. <p>If set to {@code true}, Aspose methods that save by path will attempt to create the target folder structure if it does not already exist. <p>The default value is {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
