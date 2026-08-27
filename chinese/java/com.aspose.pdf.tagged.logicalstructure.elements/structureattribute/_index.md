---
title: "StructureAttribute"
linktitle: "StructureAttribute"
second_title: "Aspose.PDF for Java API 参考"
description: "表示结构元素的属性。"
type: docs
weight: 100
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/structureattribute/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureAttribute

```
public class StructureAttribute extends Object
```

表示结构元素的属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StructureAttribute](#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | 初始化 StructureAttribute 的新实例。 |
| [StructureAttribute](#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getArrayNumberValue](#getArrayNumberValue--) | 获取 Value Number 数组。 |
| [getArrayValue](#getArrayValue--) | 获取 Value Name 数组。 |
| [getKey](#getKey--) | 获取属性键。值：Attribute Key。 |
| [getNameValue](#getNameValue--) | 获取 Value Name。 |
| [getNumberValue](#getNumberValue--) | 获取 Value Number。 |
| [getStringValue](#getStringValue--) | 获取 Value String。 |
| [isInitializedValue](#isInitializedValue--) | 获取 structure attribute value 的状态。如果已设置值，则为 true。 |
| [setArrayNumberValue](#setArrayNumberValue-java.lang.Double:A:A-) | 设置 Value Number 数组。 |
| [setArrayValue](#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName:A-) | 设置 Value Name 数组。 |
| [setColorValue](#setColorValue-com.aspose.pdf.Color-) | 设置 Value Color。 |
| [setNameValue](#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-) | 设置 Value Name。 |
| [setNumberValue](#setNumberValue-double-) | 设置 Value Number。 |
| [setRectangleValue](#setRectangleValue-com.aspose.pdf.Rectangle-) | 设置 Value Rectangle。 |
| [setStringValue](#setStringValue-java.lang.String-) | 设置 Value String。 |
| [toString](#toString--) |  |

### StructureAttribute {#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
初始化 StructureAttribute 的新实例。

### StructureAttribute {#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getArrayNumberValue {#getArrayNumberValue--}
```
public final Double [][] getArrayNumberValue()
```

获取 Value Number 数组。

**Returns:**
值编号数组。

### getArrayValue {#getArrayValue--}
```
public final AttributeName [] getArrayValue()
```

获取 Value Name 数组。

**Returns:**
值名称数组。

### getKey {#getKey--}
```
public final AttributeKey getKey()
```

获取属性键。值：Attribute Key。

**Returns:**
AttributeKey 实例

### getNameValue {#getNameValue--}
```
public final AttributeName getNameValue()
```

获取 Value Name。

**Returns:**
值名称。

### getNumberValue {#getNumberValue--}
```
public final Double [] getNumberValue()
```

获取 Value Number。

**Returns:**
值编号。

### getStringValue {#getStringValue--}
```
public final String getStringValue()
```

获取 Value String。

**Returns:**
值字符串。

### isInitializedValue {#isInitializedValue--}
```
public final boolean isInitializedValue()
```

获取 structure attribute value 的状态。如果已设置值，则为 true。

**Returns:**
布尔值

### setArrayNumberValue {#setArrayNumberValue-java.lang.Double:A:A-}
设置 Value Number 数组。

### setArrayValue {#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName:A-}
设置 Value Name 数组。

### setColorValue {#setColorValue-com.aspose.pdf.Color-}
设置 Value Color。

### setNameValue {#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-}
设置 Value Name。

### setNumberValue {#setNumberValue-double-}
```
public final void setNumberValue(double number)
```

设置 Value Number。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 |  | 值编号。 |

### setRectangleValue {#setRectangleValue-com.aspose.pdf.Rectangle-}
设置 Value Rectangle。

### setStringValue {#setStringValue-java.lang.String-}
设置 Value String。

### toString {#toString--}
```
public String toString()
```
