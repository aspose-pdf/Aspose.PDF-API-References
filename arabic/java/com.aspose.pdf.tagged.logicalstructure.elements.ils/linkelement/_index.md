---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل عنصر بنية Link في البنية المنطقية."
type: docs
weight: 70
url: /ar/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

يمثل عنصر بنية Link في البنية المنطقية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | ضبط الموضع. |
| [getHyperlink](#getHyperlink--) | يحصل أو يعيّن الارتباط التشعبي لعنصر الرابط. |
| [getStructureTextState](#getStructureTextState--) | يحصل على كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي. القيمة: كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | يحصل أو يعيّن الارتباط التشعبي لعنصر الرابط. |
| [setText](#setText-java.lang.String-) | يضيف محتوى النص إلى العنصر النصي الحالي. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
ضبط الموضع.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

يحصل أو يعيّن الارتباط التشعبي لعنصر الرابط.

**Returns:**
مثال للارتباط التشعبي

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

يحصل على كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي. القيمة: كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي.

**Returns:**
القيمة: كائن StructureTextState لعنصر بنية النص.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
يحصل أو يعيّن الارتباط التشعبي لعنصر الرابط.

### setText {#setText-java.lang.String-}
يضيف محتوى النص إلى العنصر النصي الحالي.
