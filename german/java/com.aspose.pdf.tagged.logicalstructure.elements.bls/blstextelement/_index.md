---
title: "BLSTextElement"
linktitle: "BLSTextElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Basisklasse für Block‑Ebene‑Textelemente in der logischen Struktur dar."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class BLSTextElement extends BLSElement implements ITextElement , IAdjustPosition
```

Stellt eine Basisklasse für Block‑Ebene‑Textelemente in der logischen Struktur dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Position anpassen. |
| [getStructureTextState](#getStructureTextState--) | Erhält {@code StructureTextState} Objekt für das aktuelle Element. Wert: {@code structureTextState} Objekt für das aktuelle Element. |
| [getTextFragment](#getTextFragment--) |  |
| [setText](#setText-java.lang.String-) | Fügt Textinhalt zum aktuellen Textelement hinzu. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Position anpassen.

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Erhält {@code StructureTextState} Objekt für das aktuelle Element. Wert: {@code structureTextState} Objekt für das aktuelle Element.

**Returns:**
Wert: StructureTextState Objekt für das Textelement der Struktur.

### getTextFragment {#getTextFragment--}
```
public final TextFragment getTextFragment()
```



### setText {#setText-java.lang.String-}
Fügt Textinhalt zum aktuellen Textelement hinzu.
