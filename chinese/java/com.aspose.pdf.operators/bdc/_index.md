---
title: BDC
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 BDC 运算符的类开始标记内容序列
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.operators/bdc/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class BDC extends Operator
```

表示 BDC 运算符的类（开始标记内容序列）
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BDC(String tag)](#BDC-java.lang.String-) | 初始化运算符。 |
| [BDC(int index, ICommand command)](#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 运算符类的构造函数。 |
| [BDC(String tag, IPdfDictionary properties)](#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [BDC(String tag, IPdfName property)](#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfName-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象到流程操作员。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | 获取命令 |
| [getCommandName()](#getCommandName--) | 获取操作员名称。 |
| [getIndex()](#getIndex--) | 获取页面操作符列表中的操作符索引。 |
| [getParameters()](#getParameters--) | 获取运算符参数数组。 |
| [getPropertiesDictionary()](#getPropertiesDictionary--) | 获取属性字典 |
| [getPropertiesName()](#getPropertiesName--) | 获取属性名称 |
| [getTag()](#getTag--) | 获取标记的内容标签 |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | 判断操作符是否为负责文本输出的操作符（Tj、TJ等） |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 仅供内部使用 |
| [setIndex(int value)](#setIndex-int-) | 在页面操作符列表中设置操作符索引。 |
| [setPropertiesDictionary(IPdfDictionary value)](#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-) | 设置属性字典 |
| [setPropertiesName(IPdfName value)](#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-) | 设置属性名称 |
| [setTag(String value)](#setTag-java.lang.String-) | 设置标记内容标签 |
| [toString()](#toString--) | 返回运算符的文本表示。 |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | 根据 PDF 规范返回 Pdf 原语（字符串、数组、字典等）的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BDC(String tag) {#BDC-java.lang.String-}
```
public BDC(String tag)
```


初始化运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tag | java.lang.String | 字符串标记值 |

### BDC(int index, ICommand command) {#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public BDC(int index, ICommand command)
```


运算符类的构造函数。初始化运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。 |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | 操作员命令。 |

### BDC(String tag, IPdfDictionary properties) {#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public BDC(String tag, IPdfDictionary properties)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tag | java.lang.String |  |
| properties | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### BDC(String tag, IPdfName property) {#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfName-}
```
public BDC(String tag, IPdfName property)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tag | java.lang.String |  |
| property | [IPdfName](../../com.aspose.pdf.engine.data/ipdfname) |  |

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
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


获取运算符参数数组。

**退货：**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - CommandParameter 值的 ArrayList
### getPropertiesDictionary() {#getPropertiesDictionary--}
```
public IPdfDictionary getPropertiesDictionary()
```


获取属性字典

**退货：**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdf字典值
### getPropertiesName() {#getPropertiesName--}
```
public IPdfName getPropertiesName()
```


获取属性名称

**退货：**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname) IPdfName 值
### getTag() {#getTag--}
```
public String getTag()
```


获取标记的内容标签

**退货：**
java.lang.String - 字符串值
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

### setPropertiesDictionary(IPdfDictionary value) {#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setPropertiesDictionary(IPdfDictionary value)
```


设置属性字典

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | Ipdf字典值 |

### setPropertiesName(IPdfName value) {#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-}
```
public void setPropertiesName(IPdfName value)
```


设置属性名称

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPdfName](../../com.aspose.pdf.engine.data/ipdfname) | IPdfName 值 |

### setTag(String value) {#setTag-java.lang.String-}
```
public void setTag(String value)
```


设置标记内容标签

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

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