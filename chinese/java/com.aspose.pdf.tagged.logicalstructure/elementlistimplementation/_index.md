---
title: ElementListImplementation
second_title: 用于 Java API 参考的 Aspose.PDF
description: 
type: docs
weight: 14
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.ElementList](../../com.aspose.pdf.tagged.logicalstructure/elementlist)
```
public class ElementListImplementation extends ElementList
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ElementListImplementation(Element owner)](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) |  |
| [item(int index)](#item-int-) |  |
| [iterator()](#iterator--) |  |
| [addElement(Element element, boolean updatePdfDictionary)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) |  |
| [removeElement(Element element)](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
### ElementListImplementation(Element owner) {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public ElementListImplementation(Element owner)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| owner | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

### getCount() {#getCount--}
```
public int getCount()
```


获取 ElementList 中的元素数。

**退货：**
整数
### item(int index) {#item-int-}
```
public Element item(int index)
```


检索给定索引处的元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<Element> iterator()
```


获取循环访问元素集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.tagged.logicalstructure.elements.Element>
### addElement(Element element, boolean updatePdfDictionary) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
```
public void addElement(Element element, boolean updatePdfDictionary)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |
| updatePdfDictionary | boolean |  |

### removeElement(Element element) {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void removeElement(Element element)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |
