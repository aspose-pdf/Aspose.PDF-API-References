---
title: EpubLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 包含用于将 EPUB 文件加载/导入 pdf 文档的选项。
type: docs
weight: 99
url: /zh/java/com.aspose.pdf/epubloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class EpubLoadOptions extends LoadOptions
```

包含用于将 EPUB 文件加载/导入 pdf 文档的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EpubLoadOptions()](#EpubLoadOptions--) | 创建用于将 EPUB 文件转换为 pdf 文档的默认加载选项。 |
| [EpubLoadOptions(Dimension2D pageSize)](#EpubLoadOptions-java.awt.geom.Dimension2D-) | 创建具有指定页面大小的加载选项。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getMargin()](#getMargin--) | 获取代表保证金信息的对象的引用。 |
| [getMarginsAreaUsageMode()](#getMarginsAreaUsageMode--) | 表示边距区域的使用模式 - 定义与边距使用相关的导入文档的 CSS 指令（如果有的话）的处理。 |
| [getPageSize()](#getPageSize--) | 获取导入的输出页面大小。 |
| [getPageSizeAdjustmentMode()](#getPageSizeAdjustmentMode--) | 注意力！ |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 获取代表保证金信息的对象的引用。 |
| [setMarginsAreaUsageMode(int marginsAreaUsageMode)](#setMarginsAreaUsageMode-int-) | 表示边距区域的使用模式 - 定义与边距使用相关的导入文档的 CSS 指令（如果有的话）的处理。 |
| [setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)](#setPageSizeAdjustmentMode-int-) | 注意力！ |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EpubLoadOptions() {#EpubLoadOptions--}
```
public EpubLoadOptions()
```


创建用于将 EPUB 文件转换为 pdf 文档的默认加载选项。默认 pdf 页面大小 - A4 300dpi 2480 X 3508。

### EpubLoadOptions(Dimension2D pageSize) {#EpubLoadOptions-java.awt.geom.Dimension2D-}
```
public EpubLoadOptions(Dimension2D pageSize)
```


创建具有指定页面大小的加载选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | 定义 pdf 页面宽度和高度。 |

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
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


表示 LoadOptions 描述的文件格式。

**退货：**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat 元素
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取代表保证金信息的对象的引用。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 对象
### getMarginsAreaUsageMode() {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```


表示边距区域的使用模式 - 定义与边距使用相关的导入文档的 CSS 指令（如果有的话）的处理。

**退货：**
int - MarginsAreaUsageModes 值
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


获取导入的输出页面大小。

**退货：**
java.awt.geom.Dimension2D - Dimension2D 对象
### getPageSizeAdjustmentMode() {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```


注意力！该功能已实现但尚未发布到公共 API，因为示例文档显示了 OSHARED 层中的阻止程序问题。表示转换期间页面大小的使用模式。格式（如 HTML、EPUB 等）通常采用浮动设计，因此可以适应所需的页面大小。但有时内容已指定水平位置或大小，不允许将内容放入所需的页面大小。在这种情况下，我们可以定义在这种情况下应该做什么（即当内容大小不适合结果 PDF 文档所需的初始页面大小时）。

**退货：**
int - PageSizeAdjustmentModes 值
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


获取代表保证金信息的对象的引用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setMarginsAreaUsageMode(int marginsAreaUsageMode) {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```


表示边距区域的使用模式 - 定义与边距使用相关的导入文档的 CSS 指令（如果有的话）的处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| marginsAreaUsageMode | int | MarginsAreaUsageModes 值 |

### setPageSizeAdjustmentMode(int pageSizeAdjustmentMode) {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```


注意力！该功能已实现但尚未发布到公共 API，因为示例文档显示了 OSHARED 层中的阻止程序问题。表示转换期间页面大小的使用模式。格式（如 HTML、EPUB 等）通常采用浮动设计，因此可以适应所需的页面大小。但有时内容已指定水平位置或大小，不允许将内容放入所需的页面大小。在这种情况下，我们可以定义在这种情况下应该做什么（即当内容大小不适合结果 PDF 文档所需的初始页面大小时）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSizeAdjustmentMode | int | PageSizeAdjustmentModes 值 |

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
