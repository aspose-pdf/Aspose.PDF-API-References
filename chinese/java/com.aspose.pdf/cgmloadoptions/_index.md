---
title: CgmLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 包含用于将 CGM 文件加载/导入 pdf 文档的选项。
type: docs
weight: 55
url: /zh/java/com.aspose.pdf/cgmloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class CgmLoadOptions extends LoadOptions
```

包含用于将 CGM 文件加载/导入 pdf 文档的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CgmLoadOptions()](#CgmLoadOptions--) | 创建用于将 CGM 文件转换为 pdf 文档的默认加载选项。 |
| [CgmLoadOptions(Dimension2D pageSize)](#CgmLoadOptions-java.awt.geom.Dimension2D-) | 使用定义的 pageSize 创建加载选项。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getPageSize()](#getPageSize--) | 获取导入的输出页面大小。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgmLoadOptions() {#CgmLoadOptions--}
```
public CgmLoadOptions()
```


创建用于将 CGM 文件转换为 pdf 文档的默认加载选项。默认 pdf 页面大小 - A4 300dpi 2480 X 3508。

### CgmLoadOptions(Dimension2D pageSize) {#CgmLoadOptions-java.awt.geom.Dimension2D-}
```
public CgmLoadOptions(Dimension2D pageSize)
```


使用定义的 pageSize 创建加载选项。

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
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


获取导入的输出页面大小。

**退货：**
java.awt.geom.Dimension2D - Dimension2D 对象
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
