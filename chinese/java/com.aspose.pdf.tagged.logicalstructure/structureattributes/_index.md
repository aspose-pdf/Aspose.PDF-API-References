---
title: StructureAttributes
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示标准属性所有者的结构元素的属性。
type: docs
weight: 16
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/structureattributes/
---
**遗产：**
java.lang.Object
```
public class StructureAttributes
```

表示标准属性所有者的结构元素的属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttribute(AttributeKey key)](#getAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | 通过 AttributeKey 获取 StructureAttribute。 |
| [getClass()](#getClass--) |  |
| [getEngineAttributes()](#getEngineAttributes--) |  |
| [getOwner()](#getOwner--) | 获取标准属性所有者。 |
| [hasAttribute(AttributeKey key)](#hasAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttribute(StructureAttribute attribute)](#setAttribute-com.aspose.pdf.tagged.logicalstructure.elements.StructureAttribute-) | 将 StructureAttribute 设置为 StructureAttributes。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAttribute(AttributeKey key) {#getAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public final StructureAttribute getAttribute(AttributeKey key)
```


通过 AttributeKey 获取 StructureAttribute。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) | 属性键。 |

**退货：**
[StructureAttribute](../../com.aspose.pdf.tagged.logicalstructure.elements/structureattribute) - 结构属性实例
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEngineAttributes() {#getEngineAttributes--}
```
public final IPdfDictionary getEngineAttributes()
```




**退货：**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getOwner() {#getOwner--}
```
public final AttributeOwnerStandard getOwner()
```


获取标准属性所有者。

值：标准属性所有者。

**退货：**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - AttributeOwnerStandard 实例
### hasAttribute(AttributeKey key) {#hasAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public final boolean hasAttribute(AttributeKey key)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) |  |

**退货：**
布尔值
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




### setAttribute(StructureAttribute attribute) {#setAttribute-com.aspose.pdf.tagged.logicalstructure.elements.StructureAttribute-}
```
public final void setAttribute(StructureAttribute attribute)
```


将 StructureAttribute 设置为 StructureAttributes。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attribute | [StructureAttribute](../../com.aspose.pdf.tagged.logicalstructure.elements/structureattribute) | 结构属性。 |

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
