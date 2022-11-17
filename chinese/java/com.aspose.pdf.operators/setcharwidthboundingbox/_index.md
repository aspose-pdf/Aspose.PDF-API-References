---
title: SetCharWidthBoundingBox
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 d1 运算符集字形和边界框的类。
type: docs
weight: 59
url: /zh/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetCharWidthBoundingBox extends Operator
```

表示 d1 运算符的类（设置字形和边界框）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | 初始化运算符。 |
| [SetCharWidthBoundingBox(int index, ICommand command)](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 运算符类的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象到流程操作员。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | 获取命令 |
| [getCommandName()](#getCommandName--) | 获取操作员名称。 |
| [getIndex()](#getIndex--) | 获取页面操作符列表中的操作符索引。 |
| [getLlx()](#getLlx--) | 边界矩形的左下水平坐标。 |
| [getLly()](#getLly--) | 边界矩形的左下垂直坐标。 |
| [getParameters()](#getParameters--) | 获取运算符参数数组。 |
| [getUrx()](#getUrx--) | 边界矩形的右上水平坐标。 |
| [getUry()](#getUry--) | 边界矩形的右上垂直坐标。 |
| [getWx()](#getWx--) | 字形的水平位移。 |
| [getWy()](#getWy--) | 字形的垂直位移。 |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | 判断操作符是否为负责文本输出的操作符（Tj、TJ等） |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 仅供内部使用 |
| [setIndex(int value)](#setIndex-int-) | 在页面操作符列表中设置操作符索引。 |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | 返回运算符的文本表示。 |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | 根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury) {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```


初始化运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| wx | double | 双倍价值 |
| wy | double | 双倍价值 |
| llx | double | 双倍价值 |
| lly | double | 双倍价值 |
| urx | double | 双倍价值 |
| ury | double | 双倍价值 |

### SetCharWidthBoundingBox(int index, ICommand command) {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetCharWidthBoundingBox(int index, ICommand command)
```


运算符类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。 |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | 操作员命令。 |

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
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

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
### getIndex() {#getIndex--}
```
public int getIndex()
```


获取页面操作符列表中的操作符索引。

**退货：**
int - 整数值
### getLlx() {#getLlx--}
```
public double getLlx()
```


边界矩形的左下水平坐标。

**退货：**
双倍价值
### getLly() {#getLly--}
```
public double getLly()
```


边界矩形的左下垂直坐标。

**退货：**
双倍价值
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


获取运算符参数数组。

**退货：**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - CommandParameter 值的 ArrayList
### getUrx() {#getUrx--}
```
public double getUrx()
```


边界矩形的右上水平坐标。

**退货：**
双倍价值
### getUry() {#getUry--}
```
public double getUry()
```


边界矩形的右上垂直坐标。

**退货：**
双倍价值
### getWx() {#getWx--}
```
public double getWx()
```


字形的水平位移。

**退货：**
双倍价值
### getWy() {#getWy--}
```
public double getWy()
```


字形的垂直位移。

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

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


在页面操作符列表中设置操作符索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**退货：**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
### toString() {#toString--}
```
public String toString()
```


返回运算符的文本表示。

**退货：**
java.lang.String - 表示的文本表示
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
