---
title: PsLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将 .mht 文件加载/导入 pdf 文档的选项。
type: docs
weight: 297
url: /zh/java/com.aspose.pdf/psloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class PsLoadOptions extends LoadOptions
```

表示将 .mht 文件加载/导入 pdf 文档的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PsLoadOptions()](#PsLoadOptions--) | 创建用于将 PostScript 转换为基本路径为空的 pdf 文档的加载选项。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFontsFolders()](#getFontsFolders--) | 获取字体文件夹路径。 |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFontsFolders(String[] value)](#setFontsFolders-java.lang.String---) | 设置字体文件夹路径。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsLoadOptions() {#PsLoadOptions--}
```
public PsLoadOptions()
```


创建用于将 PostScript 转换为基本路径为空的 pdf 文档的加载选项。

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
### getFontsFolders() {#getFontsFolders--}
```
public String[] getFontsFolders()
```


获取字体文件夹路径。带有用于转换的附加字体的文件夹。

**退货：**
java.lang.字符串[] - 字符串值数组
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFontsFolders(String[] value) {#setFontsFolders-java.lang.String---}
```
public void setFontsFolders(String[] value)
```


设置字体文件夹路径。带有用于转换的附加字体的文件夹。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] | 字符串值数组 |

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
