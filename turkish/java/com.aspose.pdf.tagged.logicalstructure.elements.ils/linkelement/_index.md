---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Mantıksal yapıda Link yapı öğesini temsil eder."
type: docs
weight: 70
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

Mantıksal yapıda Link yapı öğesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Pozisyonu ayarla. |
| [getHyperlink](#getHyperlink--) | Bağlantı öğesi için Hyperlink alır veya ayarlar. |
| [getStructureTextState](#getStructureTextState--) | Geçerli öğe için {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesini alır. Değer: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesi geçerli öğe için. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Bağlantı öğesi için Hyperlink alır veya ayarlar. |
| [setText](#setText-java.lang.String-) | Metin içeriğini mevcut metin öğesine ekler. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Pozisyonu ayarla.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

Bağlantı öğesi için Hyperlink alır veya ayarlar.

**Returns:**
Hyperlink örneği

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Geçerli öğe için {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesini alır. Değer: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesi geçerli öğe için.

**Returns:**
Değer: metin yapı öğesi için StructureTextState nesnesi.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Bağlantı öğesi için Hyperlink alır veya ayarlar.

### setText {#setText-java.lang.String-}
Metin içeriğini mevcut metin öğesine ekler.
