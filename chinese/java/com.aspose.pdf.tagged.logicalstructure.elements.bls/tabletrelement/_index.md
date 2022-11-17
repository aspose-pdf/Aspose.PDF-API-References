---
title: TableTRElement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示表的逻辑结构中的 TR 结构元素。
type: docs
weight: 28
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)
```
public final class TableTRElement extends TableChildElement
```

表示表的逻辑结构中的 TR 结构元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 仅供内部使用的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | 查找给定类型的元素 |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | 查找给定类型的元素 |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 将 /Aspose.Pdf.LogicalStructure.Element 附加到子集合。 |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 更改当前结构元素的父元素 |
| [clearId()](#clearId--) | 清除结构元素的 ID。 |
| [createTD()](#createTD--) | 创造[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement)并将其添加到当前表中。 |
| [createTH()](#createTH--) | 创造[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement)并将其添加到当前表中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | 为结构元素生成 ID。 |
| [getActualText()](#getActualText--) | 获取或设置结构元素的实际文本。 |
| [getAlternativeText()](#getAlternativeText--) | 获取或设置结构元素的替代文本。 |
| [getAttributes()](#getAttributes--) | 获取 StructureAttributeCollection 对象。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置行背景色。 |
| [getBorder()](#getBorder--) | 获取或设置行边框。 |
| [getChildElements()](#getChildElements--) | 获取 Element 对象的子集合。 |
| [getClass()](#getClass--) |  |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | 获取 /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。 |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | 获取默认的单元格边框。 |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | 获取或设置行单元格的默认边距。 |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | 获取或设置行单元格的默认文本状态 |
| [getElementEngine()](#getElementEngine--) | 获取父元素。 |
| [getExpansionText()](#getExpansionText--) | 获取或设置结构元素的扩展文本。 |
| [getFixedRowHeight()](#getFixedRowHeight--) | 获取固定的行高 - 行可能具有固定的高度。 |
| [getID()](#getID--) | 获取结构元素的 ID。 |
| [getLanguage()](#getLanguage--) | 获取或设置结构元素的语言。 |
| [getMinRowHeight()](#getMinRowHeight--) | 获取行的高度。 |
| [getParentElement()](#getParentElement--) | 获取 Element 对象的父集合。 |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | 获取结构元素的类型。 |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | 获取或设置结构元素的标题。 |
| [getTrailer()](#getTrailer--) | 内部法 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取或设置垂直对齐方式。 |
| [hashCode()](#hashCode--) |  |
| [isInNewPage()](#isInNewPage--) | 获取固定行在新页面中 - 具有此属性的页面应打印到下一页默认 false。 |
| [isRowBroken()](#isRowBroken--) | 获取的是两页之间可以断行。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | 获取或设置结构元素的实际文本。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 获取或设置结构元素的替代文本。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置行背景色。 |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 获取或设置行边框。 |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 获取默认的单元格边框。 |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 获取或设置行单元格的默认边距。 |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 获取或设置行单元格的默认文本状态 |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | 获取或设置结构元素的扩展文本。 |
| [setFixedRowHeight(double value)](#setFixedRowHeight-double-) | 获取固定的行高 - 行可能具有固定的高度。 |
| [setId(String id)](#setId-java.lang.String-) | 设置结构元素的 ID。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 获取固定行在新页面中 - 具有此属性的页面应打印到下一页默认 false。 |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | 获取或设置结构元素的语言。 |
| [setMinRowHeight(double value)](#setMinRowHeight-double-) | 获取行的高度。 |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 设置父元素 |
| [setRowBroken(boolean value)](#setRowBroken-boolean-) | 获取的是两页之间可以断行。 |
| [setTag(String newTag)](#setTag-java.lang.String-) | 为结构元素设置自定义标签。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 获取或设置结构元素的标题。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 获取或设置垂直对齐方式。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


仅供内部使用的构造函数

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

### createTD() {#createTD--}
```
public final TableTDElement createTD()
```


创造[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement)并将其添加到当前表中。

**退货：**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - 创建结构元素。
### createTH() {#createTH--}
```
public final TableTHElement createTH()
```


创造[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement)并将其添加到当前表中。

**退货：**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - 创建结构元素。
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
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


获取或设置行背景色。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色实例
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


获取或设置行边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 实例
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
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


获取默认的单元格边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 实例
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


获取或设置行单元格的默认边距。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 实例
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


获取或设置行单元格的默认文本状态

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
### getFixedRowHeight() {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```


获取固定的行高 - 行可能具有固定的高度。

**退货：**
双倍价值
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
### getMinRowHeight() {#getMinRowHeight--}
```
public final double getMinRowHeight()
```


获取行的高度。

**退货：**
双倍价值
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
### isInNewPage() {#isInNewPage--}
```
public final boolean isInNewPage()
```


获取固定行在新页面中 - 具有此属性的页面应打印到下一页默认 false。

**退货：**
boolean - 布尔值
### isRowBroken() {#isRowBroken--}
```
public final boolean isRowBroken()
```


获取的是两页之间可以断行。

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


获取或设置行背景色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色实例 |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


获取或设置行边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 实例 |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


获取默认的单元格边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 实例 |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


获取或设置行单元格的默认边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 实例 |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


获取或设置行单元格的默认文本状态

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

### setFixedRowHeight(double value) {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```


获取固定的行高 - 行可能具有固定的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setId(String id) {#setId-java.lang.String-}
```
public final void setId(String id)
```


设置结构元素的 ID。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 结构元素的 ID 值 |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```


获取固定行在新页面中 - 具有此属性的页面应打印到下一页默认 false。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


获取或设置结构元素的语言。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值：结构元素的语言。 |

### setMinRowHeight(double value) {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```


获取行的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


设置父元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | 价值 |

### setRowBroken(boolean value) {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```


获取的是两页之间可以断行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


获取或设置垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

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
