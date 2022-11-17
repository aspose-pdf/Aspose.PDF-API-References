---
title: ConcatenateMatrix
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 cm 运算符的类将矩阵连接到当前变换矩阵。
type: docs
weight: 23
url: /zh/java/com.aspose.pdf.operators/concatenatematrix/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class ConcatenateMatrix extends Operator
```

表示 cm 运算符的类（将矩阵连接到当前变换矩阵）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ConcatenateMatrix(int index, ICommand command)](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 运算符类的构造函数。 |
| [ConcatenateMatrix(double a, double b, double c, double d, double e, double f)](#ConcatenateMatrix-double-double-double-double-double-double-) | 运算符类的构造函数。 |
| [ConcatenateMatrix(Matrix m)](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | 通过矩阵初始化运算符。 |
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
| [getMatrix()](#getMatrix--) | 运算符的矩阵参数。 |
| [getParameters()](#getParameters--) | 获取运算符参数数组。 |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | 判断操作符是否为负责文本输出的操作符（Tj、TJ等） |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 仅供内部使用 |
| [setIndex(int value)](#setIndex-int-) | 在页面操作符列表中设置操作符索引。 |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | 运算符的矩阵参数。 |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | 返回运算符的文本表示。 |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | 根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ConcatenateMatrix(int index, ICommand command) {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ConcatenateMatrix(int index, ICommand command)
```


运算符类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。 |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | 操作员命令。 |

### ConcatenateMatrix(double a, double b, double c, double d, double e, double f) {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```


运算符类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| a | double | 一个系数 |
| b | double | B系数 |
| c | double | C系数 |
| d | double | D系数 |
| e | double | E系数 |
| f | double | F系数 |

### ConcatenateMatrix(Matrix m) {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
```
public ConcatenateMatrix(Matrix m)
```


通过矩阵初始化运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| m | [Matrix](../../com.aspose.pdf/matrix) | 变换矩阵。 |

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
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


运算符的矩阵参数。

**退货：**
[Matrix](../../com.aspose.pdf/matrix) 矩阵对象
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


获取运算符参数数组。

**退货：**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - CommandParameter 值的 ArrayList
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

### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


运算符的矩阵参数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | 矩阵对象 |

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
