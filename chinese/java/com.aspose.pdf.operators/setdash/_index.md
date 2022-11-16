---
title: SetDash
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 d 运算符集的虚线模式的类。
type: docs
weight: 67
url: /zh/java/com.aspose.pdf.operators/setdash/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetDash extends Operator
```

表示 d 运算符的类（设置虚线模式）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetDash(int index, ICommand command)](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 运算符类的构造函数。 |
| [SetDash(int[] pattern, int phase)](#SetDash-int---int-) | 创建集破折号模式运算符。 |
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
| [getParameters()](#getParameters--) | 获取运算符参数数组。 |
| [getPattern()](#getPattern--) | 破折号模式。 |
| [getPhase()](#getPhase--) | 破折号阶段。 |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | 判断操作符是否为负责文本输出的操作符（Tj、TJ等） |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 仅供内部使用 |
| [setIndex(int value)](#setIndex-int-) | 在页面操作符列表中设置操作符索引。 |
| [setPattern(int[] value)](#setPattern-int---) | 破折号模式。 |
| [setPhase(int value)](#setPhase-int-) | 破折号阶段。 |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | 获取运算符字符串表示形式。 |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | 根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetDash(int index, ICommand command) {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetDash(int index, ICommand command)
```


运算符类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。 |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | 操作员命令。 |

### SetDash(int[] pattern, int phase) {#SetDash-int---int-}
```
public SetDash(int[] pattern, int phase)
```


创建集破折号模式运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pattern | int[] | 定义虚线模式的数组。 |
| phase | int | 破折号阶段。 |

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
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


获取运算符参数数组。

**退货：**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - CommandParameter 值的 ArrayList
### getPattern() {#getPattern--}
```
public int[] getPattern()
```


破折号模式。数组的元素应为指定交替破折号和间隙长度的数字。在一个元素数组的情况下，破折号和间隙长度相等。

**退货：**
整数[] - 整数数组
### getPhase() {#getPhase--}
```
public int getPhase()
```


破折号阶段。在开始绘制路径之前，应循环破折号数组，将破折号和间隙的长度相加。当累积长度等于破折号阶段指定的值时，路径的描边应开始，破折号数组应从该点开始循环使用。

**退货：**
int - 整数值
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

### setPattern(int[] value) {#setPattern-int---}
```
public void setPattern(int[] value)
```


破折号模式。数组的元素应为指定交替破折号和间隙长度的数字。在一个元素数组的情况下，破折号和间隙长度相等。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] | 整型数组 |

### setPhase(int value) {#setPhase-int-}
```
public void setPhase(int value)
```


破折号阶段。在开始绘制路径之前，应循环破折号数组，将破折号和间隙的长度相加。当累积长度等于破折号阶段指定的值时，路径的描边应开始，破折号数组应从该点开始循环使用。

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


获取运算符字符串表示形式。

**退货：**
 java.lang.String -[x1 x2] yd，其中 x1 - 破折号长度，x2 - 间隙长度，y - 相位。
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
