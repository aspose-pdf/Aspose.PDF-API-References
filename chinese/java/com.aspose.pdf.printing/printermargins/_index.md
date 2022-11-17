---
title: PrinterMargins
second_title: 用于 Java API 参考的 Aspose.PDF
description: 指定打印页面边距的尺寸。
type: docs
weight: 19
url: /zh/java/com.aspose.pdf.printing/printermargins/
---
**遗产：**
java.lang.Object
```
public class PrinterMargins
```

指定打印页面边距的尺寸。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrinterMargins()](#PrinterMargins--) | 初始化具有 1 英寸宽边距的 Margins 类的新实例。 |
| [PrinterMargins(int left, int right, int top, int bottom)](#PrinterMargins-int-int-int-int-) | 使用指定的左、右、上和下边距初始化 Margins 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 逐个成员检索此对象的副本。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 将此 Margins 与指定的 Object 进行比较以确定它们是否具有相同的尺寸。 |
| [getBottom()](#getBottom--) | 获取或设置底部边距，以百分之一英寸为单位。 |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | 获取或设置左边距宽度，以百分之一英寸为单位。 |
| [getRight()](#getRight--) | 获取或设置右边距宽度，以百分之一英寸为单位。 |
| [getTop()](#getTop--) | 获取或设置上边距宽度，以百分之一英寸为单位。 |
| [hashCode()](#hashCode--) | 返回对象的哈希码值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PrinterMargins m1, PrinterMargins m2)](#op-Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | 比较两个边距以确定它们是否具有相同的尺寸。 |
| [op_Inequality(PrinterMargins m1, PrinterMargins m2)](#op-Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | 比较两个 Margin 以确定它们的宽度是否不等。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置底部边距，以百分之一英寸为单位。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置左边距宽度，以百分之一英寸为单位。 |
| [setRight(int value)](#setRight-int-) | 获取或设置右边距宽度，以百分之一英寸为单位。 |
| [setTop(int value)](#setTop-int-) | 获取或设置上边距宽度，以百分之一英寸为单位。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrinterMargins() {#PrinterMargins--}
```
public PrinterMargins()
```


初始化具有 1 英寸宽边距的 Margins 类的新实例。

### PrinterMargins(int left, int right, int top, int bottom) {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```


使用指定的左、右、上和下边距初始化 Margins 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| left | int | 整数值 |
| right | int | 整数值 |
| top | int | 整数值 |
| bottom | int | 整数值 |

### deepClone() {#deepClone--}
```
public PrinterMargins deepClone()
```


逐个成员检索此对象的副本。

**退货：**
[PrinterMargins](../../com.aspose.pdf.printing/printermargins) - PrinterMargins 对象
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


将此 Margins 与指定的 Object 进行比较以确定它们是否具有相同的尺寸。 （覆盖 Object.Equals(Object)。）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**退货：**
boolean - 布尔值
### getBottom() {#getBottom--}
```
public int getBottom()
```


获取或设置底部边距，以百分之一英寸为单位。

**退货：**
int - 整数值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getLeft() {#getLeft--}
```
public int getLeft()
```


获取或设置左边距宽度，以百分之一英寸为单位。

**退货：**
int - 整数值
### getRight() {#getRight--}
```
public int getRight()
```


获取或设置右边距宽度，以百分之一英寸为单位。

**退货：**
int - 整数值
### getTop() {#getTop--}
```
public int getTop()
```


获取或设置上边距宽度，以百分之一英寸为单位。

**退货：**
int - 整数值
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




### op_Equality(PrinterMargins m1, PrinterMargins m2) {#op-Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
```
public static boolean op_Equality(PrinterMargins m1, PrinterMargins m2)
```


比较两个边距以确定它们是否具有相同的尺寸。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| m1 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | PrinterMargins 对象 |
| m2 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | PrinterMargins 对象 |

**退货：**
boolean - 布尔值
### op_Inequality(PrinterMargins m1, PrinterMargins m2) {#op-Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
```
public static boolean op_Inequality(PrinterMargins m1, PrinterMargins m2)
```


比较两个 Margin 以确定它们的宽度是否不等。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| m1 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | PrinterMargins 对象 |
| m2 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | PrinterMargins 对象 |

**退货：**
boolean - 布尔值
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


获取或设置底部边距，以百分之一英寸为单位。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


获取或设置左边距宽度，以百分之一英寸为单位。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


获取或设置右边距宽度，以百分之一英寸为单位。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


获取或设置上边距宽度，以百分之一英寸为单位。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

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
