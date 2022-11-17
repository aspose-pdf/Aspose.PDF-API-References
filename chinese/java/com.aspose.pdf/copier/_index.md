---
title: Copier
second_title: 用于 Java API 参考的 Aspose.PDF
description: 应对对象类
type: docs
weight: 77
url: /zh/java/com.aspose.pdf/copier/
---
**遗产：**
java.lang.Object
```
public class Copier
```

应对对象类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Copier(ITrailerable trailerable)](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [duplicate(IPdfPrimitive src)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | 重复 IPdfPrimitive |
| [duplicate(IPdfPrimitive src, boolean IsResourceObject)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | 使用所有依赖对象创建对象副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | 获取允许重用页面内容 |
| [getClass()](#getClass--) |  |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | 忽略损坏的对象 |
| [getRestrictedKeys()](#getRestrictedKeys--) | 获取受限密钥 |
| [getReuseStreams()](#getReuseStreams--) | 获取重用流 |
| [getUseStubs()](#getUseStubs--) | 获取使用存根 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | 设置允许重复使用页面内容 |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) | 设置忽略损坏的对象 |
| [setRestrictedKeys(String[] value)](#setRestrictedKeys-java.lang.String---) | 设置限制键 |
| [setReuseStreams(boolean value)](#setReuseStreams-boolean-) | 设置重用流 |
| [setUseStubs(boolean value)](#setUseStubs-boolean-) | 设置使用存根 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Copier(ITrailerable trailerable) {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
```
public Copier(ITrailerable trailerable)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | ITrailerable对象 |

### duplicate(IPdfPrimitive src) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src)
```


重复 IPdfPrimitive

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPDF原始对象 |

**退货：**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) IPdfPrimitive 对象
### duplicate(IPdfPrimitive src, boolean IsResourceObject) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src, boolean IsResourceObject)
```


使用所有依赖对象创建对象副本。该对象可能来自其他文档的一部分（例如文档之间的复印页等）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPDF原始对象 |
| IsResourceObject | boolean | 布尔值 |

**退货：**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) IPdfPrimitive 对象
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
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```


获取允许重用页面内容

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```


忽略损坏的对象

**退货：**
boolean - 布尔值
### getRestrictedKeys() {#getRestrictedKeys--}
```
public String[] getRestrictedKeys()
```


获取受限密钥

**退货：**
java.lang.字符串[] - 细绳[大批
### getReuseStreams() {#getReuseStreams--}
```
public boolean getReuseStreams()
```


获取重用流

**退货：**
boolean - 布尔值
### getUseStubs() {#getUseStubs--}
```
public boolean getUseStubs()
```


获取使用存根

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




### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```


设置允许重复使用页面内容

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```


设置忽略损坏的对象

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRestrictedKeys(String[] value) {#setRestrictedKeys-java.lang.String---}
```
public void setRestrictedKeys(String[] value)
```


设置限制键

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.细绳[] | String[大批 |

### setReuseStreams(boolean value) {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```


设置重用流

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setUseStubs(boolean value) {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```


设置使用存根

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
