---
title: SetColorStroke
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 SC 运算符的类，为描边颜色运算符设置颜色。
type: docs
weight: 66
url: /zh/java/com.aspose.pdf.operators/setcolorstroke/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator)
```
public class SetColorStroke extends BasicSetColorOperator
```

表示 SC 运算符的类，为描边颜色运算符设置颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetColorStroke()](#SetColorStroke--) | 初始化运算符。 |
| [SetColorStroke(int index, ICommand command)](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 运算符类的构造函数。 |
| [SetColorStroke(double g)](#SetColorStroke-double-) | 为 DeviceGrey、CalGrey 和 Indexed 颜色空间的描边运算符设置颜色。 |
| [SetColorStroke(double r, double g, double b)](#SetColorStroke-double-double-double-) | 为 DeviceRGB、CalRGB 和 Lab 颜色空间的描边运算符设置颜色 |
| [SetColorStroke(double[] color)](#SetColorStroke-double---) | 允许设置颜色分量的构造函数。 |
| [SetColorStroke(double c, double m, double y, double k)](#SetColorStroke-double-double-double-double-) | 为 CMYK 颜色空间的描边运算符设置颜色 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象到流程操作员。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getB()](#getB--) | 获取颜色的红色分量 |
| [getC()](#getC--) | 获取 CMYK 颜色的青色分量。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 尚不支持。 |
| [getColorArray()](#getColorArray--) | 获取颜色分量数组。 |
| [getCommand()](#getCommand--) | 获取命令 |
| [getCommandName()](#getCommandName--) | 获取操作员名称。 |
| [getG()](#getG--) | 获取颜色的绿色分量 |
| [getGrey()](#getGrey--) | 获取灰色的黑色分量。 |
| [getIndex()](#getIndex--) | 获取页面操作符列表中的操作符索引。 |
| [getK()](#getK--) | 获取 CMYK 颜色的黑色分量。 |
| [getM()](#getM--) | 获取 CMYK 颜色的品红色分量。 |
| [getParameters()](#getParameters--) | 获取运算符参数数组。 |
| [getR()](#getR--) | 获取颜色的红色分量 |
| [getY()](#getY--) | 获取 CMYK 颜色的黄色分量。 |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | 判断操作符是否为负责文本输出的操作符（Tj、TJ等） |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 仅供内部使用 |
| [setIndex(int value)](#setIndex-int-) | 在页面操作符列表中设置操作符索引。 |
| [toString()](#toString--) | 将命令和参数转换为字符串表示形式。 |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | 根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetColorStroke() {#SetColorStroke--}
```
public SetColorStroke()
```


初始化运算符。

### SetColorStroke(int index, ICommand command) {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColorStroke(int index, ICommand command)
```


运算符类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。 |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | 操作员命令。 |

### SetColorStroke(double g) {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```


为 DeviceGrey、CalGrey 和 Indexed 颜色空间的描边运算符设置颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| g | double | 颜值。 |

### SetColorStroke(double r, double g, double b) {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```


为 DeviceRGB、CalRGB 和 Lab 颜色空间的描边运算符设置颜色

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| r | double | 红色成分。 |
| g | double | 绿色组件。 |
| b | double | 蓝色成分。 |

### SetColorStroke(double[] color) {#SetColorStroke-double---}
```
public SetColorStroke(double[] color)
```


允许设置颜色分量的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | double[] | 颜色分量数组。 |

### SetColorStroke(double c, double m, double y, double k) {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```


为 CMYK 颜色空间的描边运算符设置颜色

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| c | double | 青色成分。 |
| m | double | 洋红色成分。 |
| y | double | 黄色成分。 |
| k | double | 黑色成分。 |

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
### getB() {#getB--}
```
public double getB()
```


获取颜色的红色分量

**退货：**
双倍价值
### getC() {#getC--}
```
public double getC()
```


获取 CMYK 颜色的青色分量。

**退货：**
双倍价值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


尚不支持。

返回运算符指定的颜色。

**退货：**
[Color](../../java.awt/color) - 操作员指定的颜色。
### getColorArray() {#getColorArray--}
```
public double[] getColorArray()
```


获取颜色分量数组。

**退货：**
双倍的[] - 双数组
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
### getG() {#getG--}
```
public double getG()
```


获取颜色的绿色分量

**退货：**
双倍价值
### getGrey() {#getGrey--}
```
public double getGrey()
```


获取灰色的黑色分量。

**退货：**
双倍价值
### getIndex() {#getIndex--}
```
public int getIndex()
```


获取页面操作符列表中的操作符索引。

**退货：**
int - 整数值
### getK() {#getK--}
```
public double getK()
```


获取 CMYK 颜色的黑色分量。

**退货：**
双倍价值
### getM() {#getM--}
```
public double getM()
```


获取 CMYK 颜色的品红色分量。

**退货：**
双倍价值
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


获取运算符参数数组。

**退货：**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - CommandParameter 值的 ArrayList
### getR() {#getR--}
```
public double getR()
```


获取颜色的红色分量

**退货：**
双倍价值
### getY() {#getY--}
```
public double getY()
```


获取 CMYK 颜色的黄色分量。

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

### toString() {#toString--}
```
public String toString()
```


将命令和参数转换为字符串表示形式。

**退货：**
java.lang.String - 运算符文本
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
