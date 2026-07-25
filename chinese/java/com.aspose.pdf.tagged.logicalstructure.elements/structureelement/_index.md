---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构中结构元素的基类。"
type: docs
weight: 110
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

表示逻辑结构中结构元素的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 更改当前结构元素的父元素 |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | 更改当前结构元素的父元素 |
| [clearId](#clearId--) | 清除结构元素的 ID。 |
| [generateId](#generateId--) | 为结构元素生成 ID。 |
| [getActualText](#getActualText--) | 获取或设置结构元素的实际文本。 |
| [getAlternativeText](#getAlternativeText--) | 获取或设置结构元素的替代文本。 |
| [getAttributes](#getAttributes--) | 获取 {@code StructureAttributeCollection} 对象。 |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | 获取 {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} 对象。值：{@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} 对象。 |
| [getExpansionText](#getExpansionText--) | 获取或设置结构元素的展开文本。 |
| [getID](#getID--) | 获取结构元素的 ID。值：结构元素的 ID。 |
| [getLanguage](#getLanguage--) | 获取或设置结构元素的语言。 |
| [getPage](#getPage--) | 获取将渲染部分或全部子元素的页面。 |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | 获取结构元素的类型。 |
| [getTitle](#getTitle--) | 获取或设置结构元素的标题。 |
| [remove](#remove--) | 移除：结构中的一个元素、来自父对象的对它的引用、来自子对象的引用以及文档中对应的对象。 |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | 从结构中移除一个元素、来自父对象的对它的引用、来自子对象的引用以及文档中对应的对象。将被移除对象的子对象插入到其原父对象的子对象集合中，插入位置从被移除对象的索引开始。 |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | 从结构中移除一个元素、来自父对象的对它的引用、来自子对象的引用以及文档中对应的对象。将被移除对象的子对象插入到其原父对象的子对象集合中，插入位置从被移除对象的索引开始。 |
| [setActualText](#setActualText-java.lang.String-) | 获取或设置结构元素的实际文本。 |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | 获取或设置结构元素的替代文本。 |
| [setExpansionText](#setExpansionText-java.lang.String-) | 获取或设置结构元素的展开文本。 |
| [setId](#setId-java.lang.String-) | 设置结构元素的 ID。 |
| [setLanguage](#setLanguage-java.lang.String-) | 获取或设置结构元素的语言。 |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 设置父元素 |
| [setTag](#setTag-java.lang.String-) | 设置结构元素的自定义标签。 |
| [setTitle](#setTitle-java.lang.String-) | 获取或设置结构元素的标题。 |
| [tag](#tag-com.aspose.pdf.Annotation-) | 将结构元素绑定到 Annotation。 |
| [tag](#tag-com.aspose.pdf.Artifact-) | 将结构元素绑定到 Artifact。 |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | 将结构元素绑定到内容流 BDC 运算符。 |
| [tag](#tag-com.aspose.pdf.XForm-) | 将结构元素绑定到内容流 XForm。 |
| [tag](#tag-com.aspose.pdf.XImage-) | 将结构元素绑定到 XImage。 |
| [toString](#toString--) | 返回表示当前对象的字符串。 |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
更改当前结构元素的父元素

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
更改当前结构元素的父元素

### clearId {#clearId--}
```
public final void clearId()
```

清除结构元素的 ID。

### generateId {#generateId--}
```
public final void generateId()
```

为结构元素生成 ID。

### getActualText {#getActualText--}
```
public final String getActualText()
```

获取或设置结构元素的实际文本。

**Returns:**
值：结构元素的实际文本。

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

获取或设置结构元素的替代文本。

**Returns:**
值：结构元素的替代文本。

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

获取 {@code StructureAttributeCollection} 对象。

**Returns:**
{@code StructureAttributeCollection} 对象。

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

获取 {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} 对象。值：{@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} 对象。

**Returns:**
AttributeOwnerStandard 实例

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

获取或设置结构元素的展开文本。

**Returns:**
值：结构元素的展开文本。

### getID {#getID--}
```
public final String getID()
```

获取结构元素的 ID。值：结构元素的 ID。

**Returns:**
字符串值

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

获取或设置结构元素的语言。

**Returns:**
值：结构元素的语言。

### getPage {#getPage--}
```
public final Page getPage()
```

获取将渲染部分或全部子元素的页面。

**Returns:**
页面实例

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

获取结构元素的类型。

**Returns:**
值：结构元素的 {@code StructureTypeStandard} 对象。

### getTitle {#getTitle--}
```
public final String getTitle()
```

获取或设置结构元素的标题。

**Returns:**
值：结构元素的标题。

### remove {#remove--}
```
public final void remove()
```

移除：结构中的一个元素、来自父对象的对它的引用、来自子对象的引用以及文档中对应的对象。

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

从结构中移除一个元素、来自父对象的对它的引用、来自子对象的引用以及文档中对应的对象。将被移除对象的子对象插入到其原父对象的子对象集合中，插入位置从被移除对象的索引开始。

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

从结构中移除一个元素、来自父对象的对它的引用、来自子对象的引用以及文档中对应的对象。将被移除对象的子对象插入到其原父对象的子对象集合中，插入位置从被移除对象的索引开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | 检查是否可以将被移除对象的子对象插入到其父对象的子对象集合中。 |

### setActualText {#setActualText-java.lang.String-}
获取或设置结构元素的实际文本。

### setAlternativeText {#setAlternativeText-java.lang.String-}
获取或设置结构元素的替代文本。

### setExpansionText {#setExpansionText-java.lang.String-}
获取或设置结构元素的展开文本。

### setId {#setId-java.lang.String-}
设置结构元素的 ID。

### setLanguage {#setLanguage-java.lang.String-}
获取或设置结构元素的语言。

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
设置父元素

### setTag {#setTag-java.lang.String-}
设置结构元素的自定义标签。

### setTitle {#setTitle-java.lang.String-}
获取或设置结构元素的标题。

### tag {#tag-com.aspose.pdf.Annotation-}
将结构元素绑定到 Annotation。

### tag {#tag-com.aspose.pdf.Artifact-}
将结构元素绑定到 Artifact。

### tag {#tag-com.aspose.pdf.operators.BDC-}
将结构元素绑定到内容流 BDC 运算符。

### tag {#tag-com.aspose.pdf.XForm-}
将结构元素绑定到内容流 XForm。

### tag {#tag-com.aspose.pdf.XImage-}
将结构元素绑定到 XImage。

### toString {#toString--}
```
public String toString()
```

返回表示当前对象的字符串。

**Returns:**
表示当前对象的字符串。
