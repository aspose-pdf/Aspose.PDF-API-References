---
title: TableElement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示逻辑结构中的表结构元素。
type: docs
weight: 21
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/blselement)
```
public final class TableElement extends BLSElement
```

表示逻辑结构中的表结构元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 仅供内部使用的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | 查找给定类型的元素 |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | 查找给定类型的元素 |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 将 /Aspose.Pdf.LogicalStructure.Element 附加到子集合。 |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 更改当前结构元素的父元素 |
| [clearId()](#clearId--) | 清除结构元素的 ID。 |
| [createTBody()](#createTBody--) | 创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement)并将其添加到当前表中。 |
| [createTFoot()](#createTFoot--) | 创造[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement)并将其添加到当前表中。 |
| [createTHead()](#createTHead--) | 创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement)并将其添加到当前表中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | 为结构元素生成 ID。 |
| [getActualText()](#getActualText--) | 获取或设置结构元素的实际文本。 |
| [getAlignment()](#getAlignment--) | 获取或设置表格对齐方式。 |
| [getAlternativeText()](#getAlternativeText--) | 获取或设置结构元素的替代文本。 |
| [getAttributes()](#getAttributes--) | 获取 StructureAttributeCollection 对象。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置表格背景颜色。 |
| [getBorder()](#getBorder--) | 获取或设置表格边框。 |
| [getBroken()](#getBroken--) | 获取或设置表格垂直断开； |
| [getChildElements()](#getChildElements--) | 获取 Element 对象的子集合。 |
| [getClass()](#getClass--) |  |
| [getColumnAdjustment()](#getColumnAdjustment--) | 获取或设置表列调整。 |
| [getColumnWidths()](#getColumnWidths--) | 获取表格的列宽。 |
| [getCornerStyle()](#getCornerStyle--) | 获取或设置边框角的样式 |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | 获取 /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard 对象。 |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | 获取默认的单元格边框。 |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | 获取或设置默认的单元格填充。 |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | 获取或设置默认的单元格文本状态。 |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | 获取或设置默认列宽。 |
| [getElementEngine()](#getElementEngine--) | 获取父元素。 |
| [getExpansionText()](#getExpansionText--) | 获取或设置结构元素的扩展文本。 |
| [getID()](#getID--) | 获取结构元素的 ID。 |
| [getLanguage()](#getLanguage--) | 获取或设置结构元素的语言。 |
| [getLeft()](#getLeft--) | 获取或设置表格左侧坐标。 |
| [getParentElement()](#getParentElement--) | 获取 Element 对象的父集合。 |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | 获取或设置表的最大列数。 |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | 获取多页重复的第一行计数。 |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | 获取重复行的样式。 |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | 获取结构元素的类型。 |
| [getTable()](#getTable--) |  |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | 获取或设置结构元素的标题。 |
| [getTop()](#getTop--) | 获取或设置桌面坐标。 |
| [getTrailer()](#getTrailer--) | 内部法 |
| [hashCode()](#hashCode--) |  |
| [isBordersIncluded()](#isBordersIncluded--) | 获取或设置包含在列宽中的边框。 |
| [isBroken()](#isBroken--) | 获取或设置表格已损坏 - 将被截断以供下一页使用。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | 获取或设置结构元素的实际文本。 |
| [setAlignment(int value)](#setAlignment-int-) | 获取或设置表格对齐方式。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 获取或设置结构元素的替代文本。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置表格背景颜色。 |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 获取或设置表格边框。 |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | 获取或设置包含在列宽中的边框。 |
| [setBroken(boolean value)](#setBroken-boolean-) | 获取或设置表格已损坏 - 将被截断以供下一页使用。 |
| [setBroken(int value)](#setBroken-int-) | 获取或设置表格垂直断开； |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | 获取或设置表列调整。 |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | 获取表格的列宽。 |
| [setCornerStyle(int value)](#setCornerStyle-int-) | 获取或设置边框角的样式 |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 获取默认的单元格边框。 |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 获取或设置默认的单元格填充。 |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 获取或设置默认的单元格文本状态。 |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | 获取或设置默认列宽。 |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | 获取或设置结构元素的扩展文本。 |
| [setId(String id)](#setId-java.lang.String-) | 设置结构元素的 ID。 |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | 获取或设置结构元素的语言。 |
| [setLeft(float value)](#setLeft-float-) | 获取或设置表格左侧坐标。 |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 设置父元素 |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | 获取或设置表的最大列数。 |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | 获取多页重复的第一行计数。 |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | 获取重复行的样式。 |
| [setTag(String newTag)](#setTag-java.lang.String-) | 为结构元素设置自定义标签。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 获取或设置结构元素的标题。 |
| [setTop(float value)](#setTop-float-) | 获取或设置桌面坐标。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
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

### createTBody() {#createTBody--}
```
public final TableTBodyElement createTBody()
```


创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement)并将其添加到当前表中。

**退货：**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - 创建结构元素。
### createTFoot() {#createTFoot--}
```
public final TableTFootElement createTFoot()
```


创造[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement)并将其添加到当前表中。

**退货：**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - 创建结构元素。
### createTHead() {#createTHead--}
```
public final TableTHeadElement createTHead()
```


创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement)并将其添加到当前表中。

**退货：**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - 创建结构元素。
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


获取或设置表格对齐方式。

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


获取或设置表格背景颜色。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色实例
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


获取或设置表格边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 实例
### getBroken() {#getBroken--}
```
public final int getBroken()
```


获取或设置表格垂直断开；

**退货：**
int - TableBroken 元素
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
### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


获取或设置表列调整。

**退货：**
int - ColumnAdjustment 元素
### getColumnWidths() {#getColumnWidths--}
```
public final String getColumnWidths()
```


获取表格的列宽。

**退货：**
java.lang.String - 字符串值
### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


获取或设置边框角的样式

**退货：**
int - BorderCornerStyle 元素
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


获取或设置默认的单元格填充。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 实例
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


获取或设置默认的单元格文本状态。

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态实例
### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


获取或设置默认列宽。

**退货：**
java.lang.String - 字符串值
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
### getLeft() {#getLeft--}
```
public final float getLeft()
```


获取或设置表格左侧坐标。

**退货：**
float - 浮点值
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


获取 Element 对象的父集合。

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - 值：元素对象的父集合。
### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


获取或设置表的最大列数。

**退货：**
int - 整数值
### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


获取多页重复的第一行计数。

**退货：**
int - 整数值
### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


获取重复行的样式。

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态实例
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
### getTable() {#getTable--}
```
public final Table getTable()
```




**退货：**
[Table](../../com.aspose.pdf/table)
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
### getTop() {#getTop--}
```
public final float getTop()
```


获取或设置桌面坐标。

**退货：**
float - 浮点值
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
### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


获取或设置包含在列宽中的边框。

**退货：**
boolean - 布尔值
### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


获取或设置表格已损坏 - 将被截断以供下一页使用。

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


获取或设置表格对齐方式。

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


获取或设置表格背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色实例 |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


获取或设置表格边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 实例 |

### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


获取或设置包含在列宽中的边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


获取或设置表格已损坏 - 将被截断以供下一页使用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


获取或设置表格垂直断开；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | TableBroken 元素 |

### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


获取或设置表列调整。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 列调整元素 |

### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public final void setColumnWidths(String value)
```


获取表格的列宽。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


获取或设置边框角的样式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | BorderCornerStyle 元素 |

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


获取或设置默认的单元格填充。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 实例 |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


获取或设置默认的单元格文本状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态实例 |

### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


获取或设置默认列宽。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

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

### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


获取或设置表格左侧坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


设置父元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | 价值 |

### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


获取或设置表的最大列数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


获取多页重复的第一行计数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


获取重复行的样式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态实例 |

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

### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


获取或设置桌面坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

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
