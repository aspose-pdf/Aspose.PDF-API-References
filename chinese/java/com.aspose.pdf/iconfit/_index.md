---
title: IconFit
second_title: 用于 Java API 参考的 Aspose.PDF
description: 描述小部件注释图标应如何在其注释矩形内显示。
type: docs
weight: 164
url: /zh/java/com.aspose.pdf/iconfit/
---
**遗产：**
java.lang.Object
```
public final class IconFit
```

描述小部件注释的图标应如何在其注释矩形内显示。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeftoverBottom()](#getLeftoverBottom--) | 获取要在图标底部分配的空间。 |
| [getLeftoverLeft()](#getLeftoverLeft--) | 获取要在图标左侧分配的空间。 |
| [getScalingMode()](#getScalingMode--) | 应使用的缩放类型。 |
| [getScalingReason()](#getScalingReason--) | 获取缩放原因。 |
| [hashCode()](#hashCode--) |  |
| [isSpreadOnBorder()](#isSpreadOnBorder--) | 如果为真，则表示按钮外观应缩放以完全适合注释的边界，而不考虑边框的线宽。 |
| [nameToScalingMode(String mode)](#nameToScalingMode-java.lang.String-) | 将缩放模式名称转换为 ScalingMode 对象。 |
| [nameToScalingReason(String reason)](#nameToScalingReason-java.lang.String-) | 将缩放原因的名称转换为 ScalingReason 对象。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scalingModeToName(int mode)](#scalingModeToName-int-) | 将缩放模式对象转换为名称。 |
| [scalingReasonToName(int reason)](#scalingReasonToName-int-) | 将缩放原因对象转换为名称。 |
| [setLeftoverBottom(double value)](#setLeftoverBottom-double-) | 设置要在图标底部分配的空间。 |
| [setLeftoverLeft(double value)](#setLeftoverLeft-double-) | 设置要在图标左侧分配的空间。 |
| [setScalingMode(int value)](#setScalingMode-int-) | 应使用的缩放类型。 |
| [setScalingReason(int value)](#setScalingReason-int-) | 设置缩放原因。 |
| [setSpreadOnBorder(boolean value)](#setSpreadOnBorder-boolean-) | 如果为真，则表示按钮外观应缩放以完全适合注释的边界，而不考虑边框的线宽。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getLeftoverBottom() {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```


获取要在图标底部分配的空间。

**退货：**
double - 在底部分配空间
### getLeftoverLeft() {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```


获取要在图标左侧分配的空间。

**退货：**
double - 要在图标左侧分配的空间。
### getScalingMode() {#getScalingMode--}
```
public int getScalingMode()
```


应使用的缩放类型。

**退货：**
int - ScalingMode 值
### getScalingReason() {#getScalingReason--}
```
public int getScalingReason()
```


获取缩放原因。

**退货：**
int - ScalingReason 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isSpreadOnBorder() {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```


如果为真，则表示按钮外观应缩放以完全适合注释的边界，而不考虑边框的线宽。

**退货：**
boolean - 布尔值
### nameToScalingMode(String mode) {#nameToScalingMode-java.lang.String-}
```
public static int nameToScalingMode(String mode)
```


将缩放模式名称转换为 ScalingMode 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mode | java.lang.String | 缩放模式名称。 |

**退货：**
int - 缩放模式对象。
### nameToScalingReason(String reason) {#nameToScalingReason-java.lang.String-}
```
public static int nameToScalingReason(String reason)
```


将缩放原因的名称转换为 ScalingReason 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| reason | java.lang.String | 缩放原因的名称。 |

**退货：**
int - 缩放原因对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### scalingModeToName(int mode) {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```


将缩放模式对象转换为名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mode | int | 缩放模式对象。 |

**退货：**
java.lang.String - 缩放模式名称。
### scalingReasonToName(int reason) {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```


将缩放原因对象转换为名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| reason | int | 要转换的缩放原因对象。 |

**退货：**
java.lang.String - 缩放 reasong 的名称。
### setLeftoverBottom(double value) {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```


设置要在图标底部分配的空间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 分配在底部的空间 |

### setLeftoverLeft(double value) {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```


设置要在图标左侧分配的空间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 在图标左侧分配的空间。 |

### setScalingMode(int value) {#setScalingMode-int-}
```
public void setScalingMode(int value)
```


应使用的缩放类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ScalingMode 值 |

### setScalingReason(int value) {#setScalingReason-int-}
```
public void setScalingReason(int value)
```


设置缩放原因。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ScalingReason 值 |

### setSpreadOnBorder(boolean value) {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```


如果为真，则表示按钮外观应缩放以完全适合注释的边界，而不考虑边框的线宽。

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
