---
title: Re
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示重新运算符的类将矩形添加到路径。
type: docs
weight: 52
url: /zh/java/com.aspose.pdf.operators/re/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class Re extends Operator
```

表示 re 运算符的类（向路径添加矩形）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Re(int index, ICommand command)](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 运算符类的构造函数。 |
| [Re()](#Re--) | 用于提取目标的构造函数。 |
| [Re(double x, double y, double width, double height)](#Re-double-double-double-double-) | 编写程序的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象到流程操作员。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | 获取命令 |
| [getCommandName()](#getCommandName--) | 获取操作员名称。 |
| [getHeight()](#getHeight--) | 矩形的高度。 |
| [getIndex()](#getIndex--) | 获取页面操作符列表中的操作符索引。 |
| [getParameters()](#getParameters--) | 获取运算符参数数组。 |
| [getWidth()](#getWidth--) | 获取矩形的宽度。 |
| [getX()](#getX--) | 矩形最左侧的 X 坐标。 |
| [getY()](#getY--) | 矩形底边的 Y 坐标。 |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | 判断操作符是否为负责文本输出的操作符（Tj、TJ等） |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 仅供内部使用 |
| [setHeight(double value)](#setHeight-double-) | 矩形的高度。 |
| [setIndex(int value)](#setIndex-int-) | 在页面操作符列表中设置操作符索引。 |
| [setWidth(double value)](#setWidth-double-) | 设置矩形的宽度。 |
| [setX(double value)](#setX-double-) | 矩形最左侧的 X 坐标。 |
| [setY(double value)](#setY-double-) | 矩形底边的 Y 坐标。 |
| [toString()](#toString--) | 返回运算符的文本表示。 |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | 根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Re(int index, ICommand command) {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Re(int index, ICommand command)
```


运算符类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。 |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | 操作员命令。 |

### Re() {#Re--}
```
public Re()
```


用于提取目标的构造函数。

### Re(double x, double y, double width, double height) {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```


编写程序的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| x | double | 矩形左下角的 x 坐标。 |
| y | double | 矩形左下角的 y 坐标。 |
| width | double | 矩形的宽度。 |
| height | double | 矩形的高度。 |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


接受访问者对象到流程操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | 访客对象。 |

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
### getCommand() {#getCommand--}
```
public ICommand getCommand()
```


获取命令

**退货：**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) ICommand 对象
### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


获取操作员名称。

**退货：**
java.lang.String - 字符串值
### getHeight() {#getHeight--}
```
public double getHeight()
```


矩形的高度。

**退货：**
double - 矩形的高度。
### getIndex() {#getIndex--}
```
public int getIndex()
```


获取页面操作符列表中的操作符索引。

**退货：**
int - 整数值
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


获取运算符参数数组。

**退货：**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - CommandParameter 值的 ArrayList
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取矩形的宽度。

**退货：**
double - 矩形的宽度。
### getX() {#getX--}
```
public double getX()
```


矩形最左侧的 X 坐标。

**退货：**
双倍价值
### getY() {#getY--}
```
public double getY()
```


矩形底边的 Y 坐标。

**退货：**
双倍价值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isTextShowOperator(Operator op) {#isTextShowOperator-com.aspose.pdf.Operator-}
```
public static boolean isTextShowOperator(Operator op)
```


判断操作符是否为负责文本输出的操作符（Tj、TJ等）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 运算符对象 |

**退货：**
boolean - 如果这是文本输出运算符则为真
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


仅供内部使用

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


矩形的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 矩形的高度。 |

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


在页面操作符列表中设置操作符索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置矩形的宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 矩形的宽度。 |

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


矩形最左侧的 X 坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


矩形底边的 Y 坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### toString() {#toString--}
```
public String toString()
```


返回运算符的文本表示。

**退货：**
java.lang.String - 运算符的文本表示。
### toString(IPdfPrimitive primitive) {#toString-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static String toString(IPdfPrimitive primitive)
```


根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| primitive | [IPdf原始](../../com.aspose.pdf.engine.data/ipdfprimitive) | Primitive |

**退货：**
java.lang.String - 原语的文本表示
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
