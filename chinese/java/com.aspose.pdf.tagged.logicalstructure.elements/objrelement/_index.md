---
title: OBJRElement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示逻辑结构中的对象引用实体。
type: docs
weight: 16
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/objrelement/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public final class OBJRElement extends Element
```

表示逻辑结构中的对象引用实体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OBJRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#OBJRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | 查找给定类型的元素 |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | 查找给定类型的元素 |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 将 /Aspose.Pdf.LogicalStructure.Element 附加到子集合。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildElements()](#getChildElements--) | 获取 Element 对象的子集合。 |
| [getClass()](#getClass--) |  |
| [getElementEngine()](#getElementEngine--) | 获取父元素。 |
| [getParentElement()](#getParentElement--) | 获取 Element 对象的父集合。 |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTrailer()](#getTrailer--) | 内部法 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OBJRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#OBJRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public OBJRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) |  |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### <T>findElements(Class<T> typeOfTboolean) {#-T-findElements-java.lang.Class-T--}
```
public List<T> <T>findElements(Class<T> typeOfTboolean)
```


查找给定类型的元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| typeOfTboolean | java.lang.Class<T> | 类实例 |

**退货：**
java.util.列表<T> 找到的元素列表
### <T>findElements(Class<T> typeOfT, boolean recursiveSearch) {#-T-findElements-java.lang.Class-T--boolean-}
```
public List<T> <T>findElements(Class<T> typeOfT, boolean recursiveSearch)
```


查找给定类型的元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> | 类实例 |
| recursiveSearch | boolean | （可选）递归搜索（默认 false，仅从直接子项搜索） |

**退货：**
java.util.列表<T> 找到的元素列表
### appendChild(Element element) {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public final Element appendChild(Element element)
```


将 /Aspose.Pdf.LogicalStructure.Element 附加到子集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  /Aspose.Pdf.LogicalStructure.Element 对象添加。 |

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - 添加了/Aspose.Pdf.LogicalStructure.Element。
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
### getChildElements() {#getChildElements--}
```
public final ElementList getChildElements()
```


获取 Element 对象的子集合。

**退货：**
[ElementList](../../com.aspose.pdf.tagged.logicalstructure/elementlist) - 值：元素对象的子集合。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


获取父元素。

**退货：**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - 值：父元素。
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


获取 Element 对象的父集合。

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - 值：元素对象的父集合。
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```




**退货：**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent)
### getTrailer() {#getTrailer--}
```
public final ITrailerable getTrailer()
```


内部法

**退货：**
[ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) - 内部元素
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




### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**退货：**
java.lang.String - 表示当前对象的字符串。
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
