---
title: TableCellElement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示逻辑结构中表单元格元素 TH 和 TD 的基类。
type: docs
weight: 19
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)

**所有已实现的接口：**
[com.aspose.pdf.tagged.logicalstructure.elements.ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement)
```
public abstract class TableCellElement extends TableChildElement implements ITextElement
```

表示逻辑结构中表单元格元素（TH 和 TD）的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | 查找给定类型的元素 |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | 查找给定类型的元素 |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 将 /Aspose.Pdf.LogicalStructure.Element 附加到子集合。 |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 更改当前结构元素的父元素 |
| [clearId()](#clearId--) | 清除结构元素的 ID。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | 为结构元素生成 ID。 |
| [getActualText()](#getActualText--) | 获取或设置结构元素的实际文本。 |
| [getAlignment()](#getAlignment--) | 获取或设置单元格对齐方式。 |
| [getAlternativeText()](#getAlternativeText--) | 获取或设置结构元素的替代文本。 |
| [getAttributes()](#getAttributes--) | 获取 StructureAttributeCollection 对象。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置单元格背景颜色。 |
| [getBorder()](#getBorder--) | 获取或设置单元格边框。 |
| [getCell()](#getCell--) |  |
| [getChildElements()](#getChildElements--) | 获取 Element 对象的子集合。 |
| [getClass()](#getClass--) |  |
| [getColSpan()](#getColSpan--) | 获取或设置列跨度。 |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | 获取 /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。 |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | 获取或设置默认的单元格文本状态。 |
| [getElementEngine()](#getElementEngine--) | 获取父元素。 |
| [getExpansionText()](#getExpansionText--) | 获取或设置结构元素的扩展文本。 |
| [getID()](#getID--) | 获取结构元素的 ID。 |
| [getLanguage()](#getLanguage--) | 获取或设置结构元素的语言。 |
| [getMargin()](#getMargin--) | 获取或设置填充。 |
| [getParentElement()](#getParentElement--) | 获取 Element 对象的父集合。 |
| [getRowSpan()](#getRowSpan--) | 获取或设置行跨度。 |
| [getS()](#getS--) |  |
| [getStructureTextState()](#getStructureTextState--) | 获取当前元素的 /Aspose.Pdf.LogicalStructure.StructureTextState 对象。 |
| [getStructureType()](#getStructureType--) | 获取结构元素的类型。 |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | 获取或设置结构元素的标题。 |
| [getTrailer()](#getTrailer--) | 内部法 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取或设置垂直对齐方式。 |
| [hashCode()](#hashCode--) |  |
| [isNoBorder()](#isNoBorder--) | 获取或设置单元格是否有边框。 |
| [isWordWrapped()](#isWordWrapped--) | 获取或设置单元格的文本字换行。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | 获取或设置结构元素的实际文本。 |
| [setAlignment(int value)](#setAlignment-int-) | 获取或设置单元格对齐方式。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 获取或设置结构元素的替代文本。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置单元格背景颜色。 |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 获取或设置单元格边框。 |
| [setColSpan(int value)](#setColSpan-int-) | 获取或设置列跨度。 |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 获取或设置默认的单元格文本状态。 |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | 获取或设置结构元素的扩展文本。 |
| [setId(String id)](#setId-java.lang.String-) | 设置结构元素的 ID。 |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | 获取或设置结构元素的语言。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 获取或设置填充。 |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | 获取或设置单元格是否有边框。 |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 设置父元素 |
| [setRowSpan(int value)](#setRowSpan-int-) | 获取或设置行跨度。 |
| [setTag(String newTag)](#setTag-java.lang.String-) | 为结构元素设置自定义标签。 |
| [setText(String text)](#setText-java.lang.String-) | 将文本内容附加到当前文本元素。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 获取或设置结构元素的标题。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 获取或设置垂直对齐方式。 |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | 获取或设置单元格的文本字换行。 |
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
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


获取或设置单元格对齐方式。

**退货：**
int - HorizontalAlignment 元素
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
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


获取或设置单元格背景颜色。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色实例
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


获取或设置单元格边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 实例
### getCell() {#getCell--}
```
public final Cell getCell()
```




**退货：**
[Cell](../../com.aspose.pdf/cell)
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
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


获取或设置列跨度。

**退货：**
int - 整数值
### getDefaultAttributeOwner() {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```


获取 /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。

值：/Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。

**退货：**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - AttributeOwnerStandard 实例
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


获取或设置默认的单元格文本状态。

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态实例
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
### getMargin() {#getMargin--}
```
public final MarginInfo getMargin()
```


获取或设置填充。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 实例
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


获取 Element 对象的父集合。

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - 值：元素对象的父集合。
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```


获取或设置行跨度。

**退货：**
int - 整数值
### getS() {#getS--}
```
public final IPdfName getS()
```




**退货：**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
### getStructureTextState() {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```


获取当前元素的 /Aspose.Pdf.LogicalStructure.StructureTextState 对象。

值：当前元素的 /Aspose.Pdf.LogicalStructure.StructureTextState 对象。

**退货：**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - 结构文本状态实例
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
### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


获取或设置垂直对齐方式。

**退货：**
int - VerticalAlignment 元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isNoBorder() {#isNoBorder--}
```
public final boolean isNoBorder()
```


获取或设置单元格是否有边框。

**退货：**
boolean - 布尔值
### isWordWrapped() {#isWordWrapped--}
```
public final boolean isWordWrapped()
```


获取或设置单元格的文本字换行。

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




### setActualText(String value) {#setActualText-java.lang.String-}
```
public final void setActualText(String value)
```


获取或设置结构元素的实际文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的实际文本。 |

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


获取或设置单元格对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 元素 |

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


获取或设置结构元素的替代文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的替代文本。 |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


获取或设置单元格背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色实例 |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


获取或设置单元格边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 实例 |

### setColSpan(int value) {#setColSpan-int-}
```
public final void setColSpan(int value)
```


获取或设置列跨度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


获取或设置默认的单元格文本状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态实例 |

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

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


获取或设置填充。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 实例 |

### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```


获取或设置单元格是否有边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


设置父元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | 价值 |

### setRowSpan(int value) {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```


获取或设置行跨度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setTag(String newTag) {#setTag-java.lang.String-}
```
public final void setTag(String newTag)
```


为结构元素设置自定义标签。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newTag | java.lang.String | 标签名 |

### setText(String text) {#setText-java.lang.String-}
```
public final void setText(String text)
```


将文本内容附加到当前文本元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文字内容 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


获取或设置结构元素的标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的标题。 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


获取或设置垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```


获取或设置单元格的文本字换行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
