---
title: SetColorRenderingIntent
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 ri 运算符集颜色渲染意图的类。
type: docs
weight: 63
url: /zh/java/com.aspose.pdf.operators/setcolorrenderingintent/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetColorRenderingIntent extends Operator
```

表示 ri 运算符的类（设置颜色渲染意图）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetColorRenderingIntent()](#SetColorRenderingIntent--) | 初始化运算符。 |
| [SetColorRenderingIntent(String intentName)](#SetColorRenderingIntent-java.lang.String-) | 设置颜色渲染意图运算符构造函数。 |
| [SetColorRenderingIntent(int index, ICommand command)](#SetColorRenderingIntent-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 运算符类的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象到流程操作员。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | 获取命令 |
| [getCommandName()](#getCommandName--) | 获取操作员名称。 |
| [getIndex()](#getIndex--) | 获取页面操作符列表中的操作符索引。 |
| [getIntentName()](#getIntentName--) | 获取或设置颜色渲染意图名称。 |
| [getParameters()](#getParameters--) | 获取运算符参数数组。 |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | 判断操作符是否为负责文本输出的操作符（Tj、TJ等） |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 仅供内部使用 |
| [setIndex(int value)](#setIndex-int-) | 在页面操作符列表中设置操作符索引。 |
| [setIntentName(String value)](#setIntentName-java.lang.String-) | 获取或设置颜色渲染意图名称。 |
| [toString()](#toString--) | 将命令和参数转换为字符串表示形式。 |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | 根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetColorRenderingIntent() {#SetColorRenderingIntent--}
```
public SetColorRenderingIntent()
```


初始化运算符。

### SetColorRenderingIntent(String intentName) {#SetColorRenderingIntent-java.lang.String-}
```
public SetColorRenderingIntent(String intentName)
```


设置颜色渲染意图运算符构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| intentName | java.lang.String | 显色意图。 |

### SetColorRenderingIntent(int index, ICommand command) {#SetColorRenderingIntent-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColorRenderingIntent(int index, ICommand command)
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
### getIntentName() {#getIntentName--}
```
public String getIntentName()
```


获取或设置颜色渲染意图名称。

**退货：**
java.lang.String - 字符串对象
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

### setIntentName(String value) {#setIntentName-java.lang.String-}
```
public void setIntentName(String value)
```


获取或设置颜色渲染意图名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

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
