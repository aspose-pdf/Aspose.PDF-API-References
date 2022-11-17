---
title: StructureAttribute
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示结构元素的属性。
type: docs
weight: 17
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/structureattribute/
---
**遗产：**
java.lang.Object
```
public class StructureAttribute
```

表示结构元素的属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StructureAttribute(AttributeKey attributeKey)](#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | 初始化 StructureAttribute 的新实例。 |
| [StructureAttribute(AttributeKey attributeKey, IPdfPrimitive pdfEntity)](#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArrayNumberValue()](#getArrayNumberValue--) | 获取数值数组。 |
| [getArrayValue()](#getArrayValue--) | 获取值名称数组。 |
| [getClass()](#getClass--) |  |
| [getKey()](#getKey--) | 获取属性键。 |
| [getNameValue()](#getNameValue--) | 获取值名称。 |
| [getNumberValue()](#getNumberValue--) | 获取值编号。 |
| [getStringValue()](#getStringValue--) | 获取值字符串。 |
| [hashCode()](#hashCode--) |  |
| [isInitializedValue()](#isInitializedValue--) | 获取结构属性值的状态。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArrayNumberValue(Double[][] arrayNumber)](#setArrayNumberValue-java.lang.Double-----) | 设置数值数组。 |
| [setArrayValue(AttributeName[] array)](#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName---) | 设置值名称数组。 |
| [setColorValue(Color color)](#setColorValue-com.aspose.pdf.Color-) | 设置值颜色。 |
| [setNameValue(AttributeName name)](#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-) | 设置值名称。 |
| [setNumberValue(double number)](#setNumberValue-double-) | 设置值编号。 |
| [setRectangleValue(Rectangle rectangle)](#setRectangleValue-com.aspose.pdf.Rectangle-) | 设置值矩形。 |
| [setStringValue(String value)](#setStringValue-java.lang.String-) | 设置值字符串。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructureAttribute(AttributeKey attributeKey) {#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public StructureAttribute(AttributeKey attributeKey)
```


初始化 StructureAttribute 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attributeKey | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) | 属性键 |

### StructureAttribute(AttributeKey attributeKey, IPdfPrimitive pdfEntity) {#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public StructureAttribute(AttributeKey attributeKey, IPdfPrimitive pdfEntity)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attributeKey | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) |  |
| pdfEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

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
### getArrayNumberValue() {#getArrayNumberValue--}
```
public final Double[][] getArrayNumberValue()
```


获取数值数组。

**退货：**
java.lang.Double[][- 数值数组。
### getArrayValue() {#getArrayValue--}
```
public final AttributeName[] getArrayValue()
```


获取值名称数组。

**退货：**
com.aspose.pdf.tagged.logicalstructure.AttributeName[] - 值名称数组。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getKey() {#getKey--}
```
public final AttributeKey getKey()
```


获取属性键。

值：属性键。

**退货：**
[AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) - 属性键实例
### getNameValue() {#getNameValue--}
```
public final AttributeName getNameValue()
```


获取值名称。

**退货：**
[AttributeName](../../com.aspose.pdf.tagged.logicalstructure/attributename) - 值名称。
### getNumberValue() {#getNumberValue--}
```
public final Double[] getNumberValue()
```


获取值编号。

**退货：**
java.lang.Double[] - 值编号。
### getStringValue() {#getStringValue--}
```
public final String getStringValue()
```


获取值字符串。

**退货：**
java.lang.String - 值字符串。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isInitializedValue() {#isInitializedValue--}
```
public final boolean isInitializedValue()
```


获取结构属性值的状态。如果设置了值，则为真。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setArrayNumberValue(Double[][] arrayNumber) {#setArrayNumberValue-java.lang.Double-----}
```
public final void setArrayNumberValue(Double[][] arrayNumber)
```


设置数值数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arrayNumber | java.lang.Double[][] | 数字数组。 |

### setArrayValue(AttributeName[] array) {#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName---}
```
public final void setArrayValue(AttributeName[] array)
```


设置值名称数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [AttributeName\[\]](../../com.aspose.pdf.tagged.logicalstructure/attributename) | 允许的值名称数组。 |

### setColorValue(Color color) {#setColorValue-com.aspose.pdf.Color-}
```
public final void setColorValue(Color color)
```


设置值颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.pdf/color) | 颜色。 |

### setNameValue(AttributeName name) {#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-}
```
public final void setNameValue(AttributeName name)
```


设置值名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | [AttributeName](../../com.aspose.pdf.tagged.logicalstructure/attributename) | 允许值名称。 |

### setNumberValue(double number) {#setNumberValue-double-}
```
public final void setNumberValue(double number)
```


设置值编号。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| number | double | 值数。 |

### setRectangleValue(Rectangle rectangle) {#setRectangleValue-com.aspose.pdf.Rectangle-}
```
public final void setRectangleValue(Rectangle rectangle)
```


设置值矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | 长方形。 |

### setStringValue(String value) {#setStringValue-java.lang.String-}
```
public final void setStringValue(String value)
```


设置值字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值字符串。 |

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
