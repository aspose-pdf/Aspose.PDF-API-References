---
title: StructureAttributeCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示结构元素的属性集合。
type: docs
weight: 15
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/structureattributecollection/
---
**遗产：**
java.lang.Object
```
public class StructureAttributeCollection
```

表示结构元素的属性集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StructureAttributeCollection(IPdfPrimitive entityA, StructureElement structureElement)](#StructureAttributeCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) |  |
| [StructureAttributeCollection(StructureElement structureElement)](#StructureAttributeCollection-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createAttributes(AttributeOwnerStandard ownerStandard)](#createAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-) | 创建和返回[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes)标准属性所有者的结构元素。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes(AttributeOwnerStandard ownerStandard)](#getAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-) | 返回[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes)标准属性所有者的结构元素。 |
| [getClass()](#getClass--) |  |
| [getEngineAttributeCollection()](#getEngineAttributeCollection--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructureAttributeCollection(IPdfPrimitive entityA, StructureElement structureElement) {#StructureAttributeCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public StructureAttributeCollection(IPdfPrimitive entityA, StructureElement structureElement)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| entityA | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |
| structureElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) |  |

### StructureAttributeCollection(StructureElement structureElement) {#StructureAttributeCollection-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public StructureAttributeCollection(StructureElement structureElement)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| structureElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) |  |

### createAttributes(AttributeOwnerStandard ownerStandard) {#createAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-}
```
public final StructureAttributes createAttributes(AttributeOwnerStandard ownerStandard)
```


创建和返回[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes)标准属性所有者的结构元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerStandard | [AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) | 标准属性所有者。 |

**退货：**
[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) -[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes)的结构元素。如果需要，将创建结构属性。
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
### getAttributes(AttributeOwnerStandard ownerStandard) {#getAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-}
```
public final StructureAttributes getAttributes(AttributeOwnerStandard ownerStandard)
```


返回[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes)标准属性所有者的结构元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerStandard | [AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) | 标准属性所有者。 |

**退货：**
[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) -[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes)的结构元素。如果找不到则返回 null。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEngineAttributeCollection() {#getEngineAttributeCollection--}
```
public final IPdfPrimitive getEngineAttributeCollection()
```




**退货：**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
