---
title: XfaParserOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 处理相关数据封装的类
type: docs
weight: 412
url: /zh/java/com.aspose.pdf/xfaparseroptions/
---
**遗产：**
java.lang.Object
```
public class XfaParserOptions
```

处理相关数据封装的类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XfaParserOptions(Dimension2D pageSize)](#XfaParserOptions-java.awt.geom.Dimension2D-) | 初始化 XfaParserOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | 获取或设置基本路径。 |
| [getClass()](#getClass--) |  |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | 如果此属性为真，则将为所需的 Xfa“排除组”绘制额外的红色矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少排除组的类比。 |
| [getPageSize()](#getPageSize--) | 获取或设置页面的大小。 |
| [getSigned()](#getSigned--) | 如果此属性为真，则文档将使用 xfa 表单流（如果存在）进行转换。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasePath(URI value)](#setBasePath-java.net.URI-) | 获取或设置基本路径。 |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | 如果此属性为真，则将为所需的 Xfa“排除组”绘制额外的红色矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少排除组的类比。 |
| [setPageSize(Dimension2D value)](#setPageSize-java.awt.geom.Dimension2D-) | 获取或设置页面的大小。 |
| [setSigned(boolean value)](#setSigned-boolean-) | 如果此属性为真，则文档将使用 xfa 表单流（如果存在）进行转换。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XfaParserOptions(Dimension2D pageSize) {#XfaParserOptions-java.awt.geom.Dimension2D-}
```
public XfaParserOptions(Dimension2D pageSize)
```


初始化 XfaParserOptions 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | 页面的大小。 |

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
### getBasePath() {#getBasePath--}
```
public URI getBasePath()
```


获取或设置基本路径。

值：基本路径。

**退货：**
java.net.URI - URI 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


如果此属性为真，则将为所需的 Xfa“排除组”绘制额外的红色矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少排除组的类比。默认情况下为假。

**退货：**
boolean - 布尔值
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


获取或设置页面的大小。

值：页面的大小。

**退货：**
java.awt.geom.Dimension2D - Dimension2D 对象
### getSigned() {#getSigned--}
```
public boolean getSigned()
```


如果此属性为真，则文档将使用 xfa 表单流（如果存在）进行转换。如果它是假的，那么 xfa 表单流将被忽略。引入此属性是因为不清楚如何计算用于检查签名的校验和。

**退货：**
boolean - 布尔值
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




### setBasePath(URI value) {#setBasePath-java.net.URI-}
```
public void setBasePath(URI value)
```


获取或设置基本路径。

值：基本路径。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.net.URI | URI 对象 |

### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


如果此属性为真，则将为所需的 Xfa“排除组”绘制额外的红色矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少排除组的类比。默认情况下为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPageSize(Dimension2D value) {#setPageSize-java.awt.geom.Dimension2D-}
```
public void setPageSize(Dimension2D value)
```


获取或设置页面的大小。

值：页面的大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D | Dimension2D 对象 |

### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


如果此属性为真，则文档将使用 xfa 表单流（如果存在）进行转换。如果它是假的，那么 xfa 表单流将被忽略。引入此属性是因为不清楚如何计算用于检查签名的校验和。

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
