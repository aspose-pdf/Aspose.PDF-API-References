---
title: MCRElement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示逻辑结构中标记内容的引用对象。
type: docs
weight: 15
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public final class MCRElement extends Element
```

表示逻辑结构中标记内容的引用对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | 查找给定类型的元素 |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | 查找给定类型的元素 |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 将 /Aspose.Pdf.LogicalStructure.Element 附加到子集合。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildElements()](#getChildElements--) | 获取 Element 对象的子集合。 |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | 获取标记内容引用元素的文本内容。 |
| [getElementEngine()](#getElementEngine--) | 获取父元素。 |
| [getImageHeight()](#getImageHeight--) | 仅供内部使用 |
| [getImageResolution()](#getImageResolution--) | 仅供内部使用 |
| [getImageSrc()](#getImageSrc--) | 获取标记内容引用元素的图像源。 |
| [getImageWidth()](#getImageWidth--) | 仅供内部使用 |
| [getMCID()](#getMCID--) | 获取标记内容引用对象的 MCID。 |
| [getPage()](#getPage--) | 获取页面实例 |
| [getParentElement()](#getParentElement--) | 获取 Element 对象的父集合。 |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTrailer()](#getTrailer--) | 内部法 |
| [hashCode()](#hashCode--) |  |
| [isCreatedElement()](#isCreatedElement--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBdcOperator(BDC value)](#setBdcOperator-com.aspose.pdf.operators.BDC-) | 设置 BDC 运算符 |
| [setContent(String value)](#setContent-java.lang.String-) | 获取标记内容引用元素的文本内容。 |
| [setHyperlink(Hyperlink hyperlink)](#setHyperlink-com.aspose.pdf.Hyperlink-) |  |
| [setImageHeight(Double[] value)](#setImageHeight-java.lang.Double---) | 仅供内部使用 |
| [setImageResolution(Double[] value)](#setImageResolution-java.lang.Double---) | 仅供内部使用 |
| [setImageSrc(String value)](#setImageSrc-java.lang.String-) | 获取标记内容引用元素的图像源。 |
| [setImageWidth(Double[] value)](#setImageWidth-java.lang.Double---) | 仅供内部使用 |
| [setNewMCID(int value)](#setNewMCID-int-) | 获取 MCID 值 |
| [setPage(Page value)](#setPage-com.aspose.pdf.Page-) | 设置页面实例 |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) | TaggedContext 实例 |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | 内部实例 |

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
### getContent() {#getContent--}
```
public final String getContent()
```


获取标记内容引用元素的文本内容。

对于刚刚创建的对象至极实现[ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement).在其他情况下为空。

**退货：**
java.lang.String - 标记内容引用元素的文本内容。
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


获取父元素。

**退货：**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - 值：父元素。
### getImageHeight() {#getImageHeight--}
```
public final Double[] getImageHeight()
```


仅供内部使用

**退货：**
java.lang.Double[] - 仅供内部使用
### getImageResolution() {#getImageResolution--}
```
public final Double[] getImageResolution()
```


仅供内部使用

**退货：**
java.lang.Double[] - 仅供内部使用
### getImageSrc() {#getImageSrc--}
```
public final String getImageSrc()
```


获取标记内容引用元素的图像源。

对于刚创建的[IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement).在其他情况下为空。

**退货：**
java.lang.String - 标记内容引用元素的图像源。
### getImageWidth() {#getImageWidth--}
```
public final Double[] getImageWidth()
```


仅供内部使用

**退货：**
java.lang.Double[] - 仅供内部使用
### getMCID() {#getMCID--}
```
public final int getMCID()
```


获取标记内容引用对象的 MCID。

**退货：**
int - 标记内容引用对象的 MCID。
### getPage() {#getPage--}
```
public final Page getPage()
```


获取页面实例

**退货：**
[Page](../../com.aspose.pdf/page) - 页面实例
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
### isCreatedElement() {#isCreatedElement--}
```
public final boolean isCreatedElement()
```




**退货：**
布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBdcOperator(BDC value) {#setBdcOperator-com.aspose.pdf.operators.BDC-}
```
public final void setBdcOperator(BDC value)
```


设置 BDC 运算符

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BDC](../../com.aspose.pdf.operators/bdc) | BDC运营商 |

### setContent(String value) {#setContent-java.lang.String-}
```
public final void setContent(String value)
```


获取标记内容引用元素的文本内容。

对于刚刚创建的对象至极实现[ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement).在其他情况下为空。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 标记内容引用元素的文本内容。 |

### setHyperlink(Hyperlink hyperlink) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public final void setHyperlink(Hyperlink hyperlink)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| hyperlink | [Hyperlink](../../com.aspose.pdf/hyperlink) |  |

### setImageHeight(Double[] value) {#setImageHeight-java.lang.Double---}
```
public final void setImageHeight(Double[] value)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Double[] | 仅供内部使用 |

### setImageResolution(Double[] value) {#setImageResolution-java.lang.Double---}
```
public final void setImageResolution(Double[] value)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Double[] | 仅供内部使用 |

### setImageSrc(String value) {#setImageSrc-java.lang.String-}
```
public final void setImageSrc(String value)
```


获取标记内容引用元素的图像源。

对于刚创建的[IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement).在其他情况下为空。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 标记内容引用元素的图像源。 |

### setImageWidth(Double[] value) {#setImageWidth-java.lang.Double---}
```
public final void setImageWidth(Double[] value)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Double[] | 仅供内部使用 |

### setNewMCID(int value) {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```


获取 MCID 值

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | MCID 值 |

### setPage(Page value) {#setPage-com.aspose.pdf.Page-}
```
public final void setPage(Page value)
```


设置页面实例

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | 页面实例 |

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
