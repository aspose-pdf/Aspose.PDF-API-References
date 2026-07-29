---
title: "ILSTextElement"
linktitle: "ILSTextElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构中行内级文本结构元素的基类。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/ilstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class ILSTextElement extends ILSElement implements ITextElement , IAdjustPosition
```

表示逻辑结构中行内级文本结构元素的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 调整位置。 |
| [getStructureTextState](#getStructureTextState--) | 获取当前元素的 {@code StructureTextState} 对象。值：当前元素的 {@code StructureTextState} 对象。 |
| [setText](#setText-java.lang.String-) | 将文本内容追加到当前文本元素。 |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
调整位置。

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

获取当前元素的 {@code StructureTextState} 对象。值：当前元素的 {@code StructureTextState} 对象。

**Returns:**
值：文本结构元素的 StructureTextState 对象。

### setText {#setText-java.lang.String-}
将文本内容追加到当前文本元素。
