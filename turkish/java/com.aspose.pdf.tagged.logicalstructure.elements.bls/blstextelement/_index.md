---
title: "BLSTextElement"
linktitle: "BLSTextElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Mantıksal yapıda blok seviyesindeki metin yapı öğeleri için temel sınıfı temsil eder."
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class BLSTextElement extends BLSElement implements ITextElement , IAdjustPosition
```

Mantıksal yapıda blok seviyesindeki metin yapı öğeleri için temel sınıfı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Pozisyonu ayarla. |
| [getStructureTextState](#getStructureTextState--) | Mevcut öğe için {@code StructureTextState} nesnesini alır. Değer: mevcut öğe için {@code structureTextState} nesnesi. |
| [getTextFragment](#getTextFragment--) |  |
| [setText](#setText-java.lang.String-) | Metin içeriğini mevcut metin öğesine ekler. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Pozisyonu ayarla.

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Mevcut öğe için {@code StructureTextState} nesnesini alır. Değer: mevcut öğe için {@code structureTextState} nesnesi.

**Returns:**
Değer: metin yapı öğesi için StructureTextState nesnesi.

### getTextFragment {#getTextFragment--}
```
public final TextFragment getTextFragment()
```



### setText {#setText-java.lang.String-}
Metin içeriğini mevcut metin öğesine ekler.
