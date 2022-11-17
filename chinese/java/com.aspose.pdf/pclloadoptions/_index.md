---
title: PclLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将 PCL 文件加载到 pdf 文档的选项。
type: docs
weight: 273
url: /zh/java/com.aspose.pdf/pclloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)

**所有已实现的接口：**
[com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

表示将 PCL 文件加载（导入）到 pdf 文档中的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PclLoadOptions()](#PclLoadOptions--) | 创建 PclLoadOptions 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBatchSize()](#getBatchSize--) | 如果批量转换适用于源格式和目标格式对，则定义批量大小。 |
| [getClass()](#getClass--) |  |
| [getConversionEngine()](#getConversionEngine--) | 定义将用于转换的转换引擎 |
| [getExceptions()](#getExceptions--) | 转换错误列表。 |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isSupressErrors()](#isSupressErrors--) | 获取或设置布尔值，该值指示应抑制 PCL 转换错误。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBatchSize(int value)](#setBatchSize-int-) | 如果批量转换适用于源格式和目标格式对，则定义批量大小。 |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | 定义将用于转换的转换引擎 |
| [setSupressErrors(boolean supressErrors)](#setSupressErrors-boolean-) | 获取或设置布尔值，该值指示应抑制 PCL 转换错误。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PclLoadOptions() {#PclLoadOptions--}
```
public PclLoadOptions()
```


创建 PclLoadOptions 对象。

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
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


如果批量转换适用于源格式和目标格式对，则定义批量大小。

**退货：**
int - 整数值
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


定义将用于转换的转换引擎

**退货：**
int - ConversionEngines 元素
### getExceptions() {#getExceptions--}
```
public List<Exception> getExceptions()
```


转换错误列表。

**退货：**
java.util.List<java.lang.Exception> - 异常列表
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


表示 LoadOptions 描述的文件格式。

**退货：**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat 元素
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
### isSupressErrors() {#isSupressErrors--}
```
public boolean isSupressErrors()
```


获取或设置布尔值，该值指示应抑制 PCL 转换错误。

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




### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


如果批量转换适用于源格式和目标格式对，则定义批量大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


定义将用于转换的转换引擎

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversionEngine | int | ConversionEngines 元素 |

### setSupressErrors(boolean supressErrors) {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```


获取或设置布尔值，该值指示应抑制 PCL 转换错误。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| supressErrors | boolean | 布尔值 |

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
