---
title: WarningCallback
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用户回调机制支持接口。
type: docs
weight: 398
url: /zh/java/com.aspose.pdf/warningcallback/
---
**遗产：**
java.lang.Object
```
public abstract class WarningCallback
```

用户回调机制支持接口。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WarningCallback()](#WarningCallback--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warning(WarningInfo warning)](#warning-com.aspose.pdf.WarningInfo-) | 一些程序通知的回调方法。 |
### WarningCallback() {#WarningCallback--}
```
public WarningCallback()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
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

### warning(WarningInfo warning) {#warning-com.aspose.pdf.WarningInfo-}
```
public abstract WarningCallback.ReturnAction warning(WarningInfo warning)
```


一些程序通知的回调方法。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| warning | [WarningInfo](../../com.aspose.pdf/warninginfo) | 某些发生警告的警告信息 |

**退货：**
[ReturnAction](../../com.aspose.pdf/returnaction) 进一步程序工作流程的结果