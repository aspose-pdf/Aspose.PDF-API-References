---
title: SvgLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将 SVG 文件加载/导入 pdf 文档的选项。
type: docs
weight: 343
url: /zh/java/com.aspose.pdf/svgloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class SvgLoadOptions extends LoadOptions
```

表示将 SVG 文件加载/导入 pdf 文档的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgLoadOptions()](#SvgLoadOptions--) | 创建 SvgLoadOptions 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConversionEngine()](#getConversionEngine--) | 允许选择将在转换期间使用的转换引擎。 |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getPageInfo()](#getPageInfo--) | 获取应在加载文档期间应用的页面信息。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isAdjustPageSize()](#isAdjustPageSize--) | 将 pdf 页面大小调整为 svg 大小 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdjustPageSize(boolean value)](#setAdjustPageSize-boolean-) | 将 pdf 页面大小调整为 svg 大小 |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | 允许选择将在转换期间使用的转换引擎。 |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置应在加载文档期间应用的页面信息。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgLoadOptions() {#SvgLoadOptions--}
```
public SvgLoadOptions()
```


创建 SvgLoadOptions 对象。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getConversionEngine() {#getConversionEngine--}
```
public int getConversionEngine()
```


允许选择将在转换期间使用的转换引擎。目前新引擎处于B-testing阶段，所以这个值默认设置为ConversionEngines.LegacyEngine

**退货：**
int - ConversionEngines 元素
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


表示 LoadOptions 描述的文件格式。

**退货：**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat 元素
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


获取应在加载文档期间应用的页面信息。请注意，此参数仅在 ConversionEngine == ConversionEngines.NewEngine 时有效

**退货：**
[PageInfo](../../com.aspose.pdf/pageinfo) 页面信息对象
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

**退货：**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isAdjustPageSize() {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```


将 pdf 页面大小调整为 svg 大小

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




### setAdjustPageSize(boolean value) {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```


将 pdf 页面大小调整为 svg 大小

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


允许选择将在转换期间使用的转换引擎。目前新引擎处于B-testing阶段，所以这个值默认设置为ConversionEngines.LegacyEngine

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversionEngine | int | ConversionEngines 元素 |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


设置应在加载文档期间应用的页面信息。请注意，此参数仅在 ConversionEngine == ConversionEngines.NewEngine 时有效

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo 对象 |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback 值 |

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
