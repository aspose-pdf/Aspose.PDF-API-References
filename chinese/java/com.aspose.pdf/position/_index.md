---
title: Position
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示一个位置对象
type: docs
weight: 291
url: /zh/java/com.aspose.pdf/position/
---
**遗产：**
java.lang.Object
```
public final class Position
```

表示一个位置对象
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Position(double xIndent, double yIndent)](#Position-double-double-) | 初始化 Position 类的新实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定对象是否等于当前 Position 对象。 |
| [getClass()](#getClass--) |  |
| [getXIndent()](#getXIndent--) | 获取对象的X坐标 |
| [getYIndent()](#getYIndent--) | 获取对象的Y坐标 |
| [hashCode()](#hashCode--) | 返回对象的哈希码值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setXIndent(double value)](#setXIndent-double-) | 设置对象的 X 坐标 |
| [setYIndent(double value)](#setYIndent-double-) | 设置对象的 Y 坐标 |
| [toString()](#toString--) | 获取当前 Position 对象的字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Position(double xIndent, double yIndent) {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```


初始化 Position 类的新实例

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xIndent | double | X 坐标值。 |
| yIndent | double | Y 坐标值。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定对象是否等于当前 Position 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 检查是否相等的对象。 |

**退货：**
boolean - 如果对象相等则为真。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


获取对象的X坐标

**退货：**
双倍价值
### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


获取对象的Y坐标

**退货：**
双倍价值
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回对象的哈希码值。支持此方法是为了散列表的好处，例如 java.util.HashMap 提供的散列表。

hashCode的一般契约是：

 *  每当在 Java 应用程序的执行期间对同一对象多次调用它时，hashCode 方法必须一致地返回相同的整数，前提是在对象的 equals 比较中使用的信息没有被修改。从一个应用程序的一次执行到同一应用程序的另一次执行，该整数不需要保持一致。
 *  如果根据 equals(Object) 方法两个对象相等，则对这两个对象中的每一个调用 hashCode 方法必须产生相同的整数结果。
 *  这是*not*要求如果两个对象根据 java.lang.Object 不相等\#equals(java.lang.Object).equals(java.lang.Object) 方法，然后在两个对象中的每一个上调用 hashCode 方法必须产生不同的整数结果。但是，程序员应该知道，为不相等的对象生成不同的整数结果可能会提高哈希表的性能。

在相当实用的情况下，类 Object 定义的 hashCode 方法确实会为不同的对象返回不同的整数。 （这通常是通过将对象的内部地址转换为整数来实现的，但 JavaTM 编程语言不需要这种实现技术。）

**退货：**
int - 此对象的哈希码值。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


设置对象的 X 坐标

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


设置对象的 Y 坐标

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### toString() {#toString--}
```
public String toString()
```


获取当前 Position 对象的字符串表示形式。

**退货：**
java.lang.String - Position 对象的字符串表示。
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
