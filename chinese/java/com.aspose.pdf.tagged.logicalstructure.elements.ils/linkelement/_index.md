---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构中的 Link 结构元素。"
type: docs
weight: 70
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

表示逻辑结构中的 Link 结构元素。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 调整位置。 |
| [getHyperlink](#getHyperlink--) | 获取或设置链接元素的超链接。 |
| [getStructureTextState](#getStructureTextState--) | 获取当前元素的 {@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象。值：{@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象用于当前元素。 |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | 获取或设置链接元素的超链接。 |
| [setText](#setText-java.lang.String-) | 将文本内容追加到当前文本元素。 |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
调整位置。

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

获取或设置链接元素的超链接。

**Returns:**
超链接实例

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

获取当前元素的 {@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象。值：{@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象用于当前元素。

**Returns:**
值：文本结构元素的 StructureTextState 对象。

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
获取或设置链接元素的超链接。

### setText {#setText-java.lang.String-}
将文本内容追加到当前文本元素。
