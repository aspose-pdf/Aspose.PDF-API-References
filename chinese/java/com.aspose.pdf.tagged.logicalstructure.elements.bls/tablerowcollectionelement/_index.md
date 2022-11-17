---
title: TableRowCollectionElement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 在逻辑结构中表示 Table Head Body 和 Foot 的子元素的基类。
type: docs
weight: 22
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablerowcollectionelement/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)
```
public abstract class TableRowCollectionElement extends TableChildElement
```

在逻辑结构中表示 Table Head、Body 和 Foot 的子元素的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | 查找给定类型的元素 |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | 查找给定类型的元素 |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 将 /Aspose.Pdf.LogicalStructure.Element 附加到子集合。 |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 更改当前结构元素的父元素 |
| [clearId()](#clearId--) | 清除结构元素的 ID。 |
| [createTR()](#createTR--) | 创造[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement)并将其添加到当前表中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | 为结构元素生成 ID。 |
| [getActualText()](#getActualText--) | 获取或设置结构元素的实际文本。 |
| [getAlternativeText()](#getAlternativeText--) | 获取或设置结构元素的替代文本。 |
| [getAttributes()](#getAttributes--) | 获取 StructureAttributeCollection 对象。 |
| [getChildElements()](#getChildElements--) | 获取 Element 对象的子集合。 |
| [getClass()](#getClass--) |  |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | 获取 /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。 |
| [getElementEngine()](#getElementEngine--) | 获取父元素。 |
| [getExpansionText()](#getExpansionText--) | 获取或设置结构元素的扩展文本。 |
| [getID()](#getID--) | 获取结构元素的 ID。 |
| [getLanguage()](#getLanguage--) | 获取或设置结构元素的语言。 |
| [getParentElement()](#getParentElement--) | 获取 Element 对象的父集合。 |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | 获取结构元素的类型。 |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | 获取或设置结构元素的标题。 |
| [getTrailer()](#getTrailer--) | 内部法 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | 获取或设置结构元素的实际文本。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 获取或设置结构元素的替代文本。 |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | 获取或设置结构元素的扩展文本。 |
| [setId(String id)](#setId-java.lang.String-) | 设置结构元素的 ID。 |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | 获取或设置结构元素的语言。 |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 设置父元素 |
| [setTag(String newTag)](#setTag-java.lang.String-) | 为结构元素设置自定义标签。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 获取或设置结构元素的标题。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### changeParentElement(StructureElement newParentElement) {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public final void changeParentElement(StructureElement newParentElement)
```


更改当前结构元素的父元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newParentElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) | 新的父结构元素 |

### clearId() {#clearId--}
```
public final void clearId()
```


清除结构元素的 ID。

### createTR() {#createTR--}
```
public TableTRElement createTR()
```


创造[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement)并将其添加到当前表中。

**退货：**
[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement) - 创建结构元素。
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
### generateId() {#generateId--}
```
public final void generateId()
```


为结构元素生成 ID。

### getActualText() {#getActualText--}
```
public final String getActualText()
```


获取或设置结构元素的实际文本。

**退货：**
java.lang.String - 值：结构元素的实际文本。
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取或设置结构元素的替代文本。

**退货：**
java.lang.String - 值：结构元素的替代文本。
### getAttributes() {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```


获取 StructureAttributeCollection 对象。

**退货：**
[StructureAttributeCollection](../../com.aspose.pdf.tagged.logicalstructure/structureattributecollection) - StructureAttributeCollection 对象。
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
### getDefaultAttributeOwner() {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```


获取 /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。

值：/Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。

**退货：**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - AttributeOwnerStandard 实例
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


获取父元素。

**退货：**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - 值：父元素。
### getExpansionText() {#getExpansionText--}
```
public final String getExpansionText()
```


获取或设置结构元素的扩展文本。

**退货：**
java.lang.String - 值：结构元素的扩展文本。
### getID() {#getID--}
```
public final String getID()
```


获取结构元素的 ID。

值：结构元素的 ID。

**退货：**
java.lang.String - 字符串值
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


获取或设置结构元素的语言。

**退货：**
java.lang.String - 值：结构元素的语言。
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


获取 Element 对象的父集合。

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - 值：元素对象的父集合。
### getS() {#getS--}
```
public final IPdfName getS()
```




**退货：**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
### getStructureType() {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```


获取结构元素的类型。

**退货：**
[StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard) - 值：结构元素的 StructureTypeStandard 对象。
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```




**退货：**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent)
### getTitle() {#getTitle--}
```
public final String getTitle()
```


获取或设置结构元素的标题。

**退货：**
java.lang.String - 值：结构元素的标题。
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




### setActualText(String value) {#setActualText-java.lang.String-}
```
public final void setActualText(String value)
```


获取或设置结构元素的实际文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的实际文本。 |

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


获取或设置结构元素的替代文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的替代文本。 |

### setExpansionText(String value) {#setExpansionText-java.lang.String-}
```
public final void setExpansionText(String value)
```


获取或设置结构元素的扩展文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的扩展文本。 |

### setId(String id) {#setId-java.lang.String-}
```
public final void setId(String id)
```


设置结构元素的 ID。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 结构元素的 ID 值 |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


获取或设置结构元素的语言。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的语言。 |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


设置父元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | 价值 |

### setTag(String newTag) {#setTag-java.lang.String-}
```
public final void setTag(String newTag)
```


为结构元素设置自定义标签。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newTag | java.lang.String | 标签名 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


获取或设置结构元素的标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的标题。 |

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
