---
title: Group
second_title: 用于 Java API 参考的 Aspose.PDF
description: 一个组属性类，指定用于透明成像模型的 pageu2019s 页组的属性。
type: docs
weight: 148
url: /zh/java/com.aspose.pdf/group/
---
**遗产：**
java.lang.Object
```
public final class Group
```

指定页面属性的组属性类\用于透明成像模型的页组。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Group(Page page)](#Group-com.aspose.pdf.Page-) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | 获取色彩空间 |
| [hashCode()](#hashCode--) |  |
| [isKnockout()](#isKnockout--) | 仅供内部使用 |
| [isTransparency()](#isTransparency--) | 仅供内部使用 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorSpace(int value)](#setColorSpace-int-) | 组色彩空间。 |
| [setKnockout(int value)](#setKnockout-int-) | 如果此标志为假，则组中后面的对象将与它们重叠的较早对象合成；如果为真，则它们与组合成\\u2019s 初始背景并覆盖 (\\u201cknock out\\u201d) 任何较早的重叠对象。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Group(Page page) {#Group-com.aspose.pdf.Page-}
```
public Group(Page page)
```


构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF 页面对象。 |

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
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


获取色彩空间

**退货：**
int - 颜色空间值。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isKnockout() {#isKnockout--}
```
public int isKnockout()
```


仅供内部使用

如果此标志为假，则组中后面的对象将与它们重叠的较早对象合成；如果为真，则它们与组合成\\u2019s 初始背景并覆盖 (\\u201cknock out\\u201d) 任何较早的重叠对象。

**退货：**
int - ExtendedBoolean 元素
### isTransparency() {#isTransparency--}
```
public boolean isTransparency()
```


仅供内部使用

返回组透明度标志。

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




### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


组色彩空间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 色彩空间值。 |

### setKnockout(int value) {#setKnockout-int-}
```
public void setKnockout(int value)
```


如果此标志为假，则组中后面的对象将与它们重叠的较早对象合成；如果为真，则它们与组合成\\u2019s 初始背景并覆盖 (\\u201cknock out\\u201d) 任何较早的重叠对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 扩展布尔元素 |

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
