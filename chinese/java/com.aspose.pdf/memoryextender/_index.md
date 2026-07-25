---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 MemoryExtender 类。在堆内存受限的系统上使用大文件时，可以启用它使用磁盘空间作为临时交换内存。"
type: docs
weight: 3020
url: /zh/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

表示 MemoryExtender 类。在堆内存受限的系统上使用大文件时，可以启用它使用磁盘空间作为临时交换内存。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | 获取自定义缓存分析器。 |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | 用于页面转图像转换的单个元素渲染的最大时间。默认值 10000 毫秒。仅在 isSkipHeavyContentEnabled() == true 时使用。 |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | 获取 EnabledMultiPageImageCache 字段的状态 |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | 是否启用 OptimizedMemoryStream 作为默认内存存储。处理超过 2 GB 的大文档时需要。默认值为 FALSE。 |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | 是否启用 OptimizedMemoryStream 作为默认内存存储。处理超过 2 GB 的大文档时需要。默认值为 FALSE。 |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | 是否启用在堆内存不足的渲染中跳过高内存消耗的对象。默认值为 FALSE。 |
| [isSwapEnabled](#isSwapEnabled--) | 是否启用使用磁盘空间作为临时交换内存。默认值为 FALSE。 |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | 获取一个值，指示是否应自动创建缺失的文件夹。<p>If set to {@code true}, Aspose 按路径保存的方法将在目标文件夹结构不存在时尝试创建它。<p>默认值为 {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | 应用新的自定义缓存分析器。 |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | 用于页面转图像转换的单个元素渲染的最大时间。默认值 10000 毫秒，仅在 isSkipHeavyContentEnabled() == true 时使用。 |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | 设置 EnabledMultiPageImageCache 字段的新状态 |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | 设置标志以在堆内存不足的渲染中跳过高内存消耗的对象。 |
| [setSwapEnabled](#setSwapEnabled-boolean-) | 设置标志以启用使用磁盘空间作为临时交换内存。 |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | 设置一个值，指示是否应自动创建缺失的文件夹。<p>If set to {@code true}, Aspose 按路径保存的方法将在目标文件夹结构不存在时尝试创建它。<p>默认值为 {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

获取自定义缓存分析器。

**Returns:**
CallBackPageImage 对象

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

用于页面转图像转换的单个元素渲染的最大时间。默认值 10000 毫秒。仅在 isSkipHeavyContentEnabled() == true 时使用。

**Returns:**
int 值 毫秒数

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

获取 EnabledMultiPageImageCache 字段的状态

**Returns:**
布尔值

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

是否启用 OptimizedMemoryStream 作为默认内存存储。处理超过 2 GB 的大文档时需要。默认值为 FALSE。

**Returns:**
布尔值

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

是否启用 OptimizedMemoryStream 作为默认内存存储。处理超过 2 GB 的大文档时需要。默认值为 FALSE。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

是否启用在堆内存不足的渲染中跳过高内存消耗的对象。默认值为 FALSE。

**Returns:**
布尔值

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

是否启用使用磁盘空间作为临时交换内存。默认值为 FALSE。

**Returns:**
布尔值

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

获取一个值，指示是否应自动创建缺失的文件夹。<p>If set to {@code true}, Aspose 按路径保存的方法将在目标文件夹结构不存在时尝试创建它。<p>默认值为 {@code false}.

**Returns:**
布尔值

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
应用新的自定义缓存分析器。

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

用于页面转图像转换的单个元素渲染的最大时间。默认值 10000 毫秒，仅在 isSkipHeavyContentEnabled() == true 时使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 毫秒数 |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

设置 EnabledMultiPageImageCache 字段的新状态

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | 布尔值 |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

设置标志以在堆内存不足的渲染中跳过高内存消耗的对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

设置标志以启用使用磁盘空间作为临时交换内存。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

设置一个值，指示是否应自动创建缺失的文件夹。<p>If set to {@code true}, Aspose 按路径保存的方法将在目标文件夹结构不存在时尝试创建它。<p>默认值为 {@code false}.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
