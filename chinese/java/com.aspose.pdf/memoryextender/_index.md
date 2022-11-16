---
title: MemoryExtender
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 MemoryExtender 类 Using large files on a system with limited heap memory 可以启用将磁盘空间用作临时交换内存。
type: docs
weight: 218
url: /zh/java/com.aspose.pdf/memoryextender/
---
**遗产：**
java.lang.Object
```
public class MemoryExtender
```

表示 MemoryExtender 类 在堆内存有限的系统上使用大文件，可以启用将磁盘空间用作临时交换内存。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MemoryExtender()](#MemoryExtender--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCallBackPageImage()](#getCallBackPageImage--) | 获取自定义缓存分析器。 |
| [getClass()](#getClass--) |  |
| [getElementRenderingTimeout()](#getElementRenderingTimeout--) | 渲染页面到图像转换中使用的单个元素的最长时间。 |
| [hashCode()](#hashCode--) |  |
| [isEnabledMultiPageImageCache()](#isEnabledMultiPageImageCache--) | 获取 EnabledMultiPageImageCache 字段的状态 |
| [isOptimizedMemoryStreamByDefault()](#isOptimizedMemoryStreamByDefault--) | 启用以使用 OptimizedMemoryStream 作为默认内存存储。 |
| [isOptimizedMemoryStreamByDefault(boolean value)](#isOptimizedMemoryStreamByDefault-boolean-) | 启用以使用 OptimizedMemoryStream 作为默认内存存储。 |
| [isSkipHeavyContentEnabled()](#isSkipHeavyContentEnabled--) | 启用以在缺少堆内存的情况下跳过渲染中内存消耗高的对象。 |
| [isSwapEnabled()](#isSwapEnabled--) | 启用以将磁盘空间用作临时交换内存。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_)](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | 应用新的自定义缓存分析器。 |
| [setElementRenderingTimeout(int value)](#setElementRenderingTimeout-int-) | 渲染页面到图像转换中使用的单个元素的最长时间。 |
| [setEnableMultiPageCache(boolean enableMultiPageImageCache_)](#setEnableMultiPageCache-boolean-) | 为 EnabledMultiPageImageCache 字段设置新状态 |
| [setSkipHeavyContentEnabled(boolean value)](#setSkipHeavyContentEnabled-boolean-) | 设置标志以启用在缺少堆内存的情况下跳过渲染中内存消耗高的对象。 |
| [setSwapEnabled(boolean value)](#setSwapEnabled-boolean-) | 设置标志是否启用磁盘空间以用作临时交换内存。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MemoryExtender() {#MemoryExtender--}
```
public MemoryExtender()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getCallBackPageImage() {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```


获取自定义缓存分析器。

**退货：**
[CallBackPageImage](../../com.aspose.pdf/callbackpageimage) - CallBackPageImage 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getElementRenderingTimeout() {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```


渲染页面到图像转换中使用的单个元素的最长时间。默认值 10000 毫秒。仅在 isSkipHeavyContentEnabled() == true 时使用

**退货：**
int - int 值 毫秒数
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isEnabledMultiPageImageCache() {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```


获取 EnabledMultiPageImageCache 字段的状态

**退货：**
boolean - 布尔值
### isOptimizedMemoryStreamByDefault() {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```


启用以使用 OptimizedMemoryStream 作为默认内存存储。处理超过 2 Gb 的大型文档时需要。默认值为 FALSE

**退货：**
boolean - 布尔值
### isOptimizedMemoryStreamByDefault(boolean value) {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```


启用以使用 OptimizedMemoryStream 作为默认内存存储。处理超过 2 Gb 的大型文档时需要。默认值为 FALSE

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### isSkipHeavyContentEnabled() {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```


启用以在缺少堆内存的情况下跳过渲染中内存消耗高的对象。默认值为 FALSE

**退货：**
boolean - 布尔值
### isSwapEnabled() {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```


启用以将磁盘空间用作临时交换内存。默认值为 FALSE

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_) {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
```
public static void setCallBackPageImage(MemoryExtender.CallBackPageImage callBackPageImage_)
```


应用新的自定义缓存分析器。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callBackPageImage_ | [CallBackPageImage](../../com.aspose.pdf/callbackpageimage) | CallBackPageImage 对象 |

### setElementRenderingTimeout(int value) {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```


渲染页面到图像转换中使用的单个元素的最长时间。默认值 10000 毫秒仅在 isSkipHeavyContentEnabled() == true 时使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | int 值 毫秒数 |

### setEnableMultiPageCache(boolean enableMultiPageImageCache_) {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```


为 EnabledMultiPageImageCache 字段设置新状态

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| enableMultiPageImageCache_ | 布尔值 | 布尔值 |

### setSkipHeavyContentEnabled(boolean value) {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```


设置标志以启用在缺少堆内存的情况下跳过渲染中内存消耗高的对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSwapEnabled(boolean value) {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```


设置标志是否启用磁盘空间以用作临时交换内存。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
