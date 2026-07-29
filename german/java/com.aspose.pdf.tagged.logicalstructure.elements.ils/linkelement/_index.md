---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt das Link‑Strukturelement in der logischen Struktur dar."
type: docs
weight: 70
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

Stellt das Link‑Strukturelement in der logischen Struktur dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Position anpassen. |
| [getHyperlink](#getHyperlink--) | Liest oder setzt den Hyperlink für das Link-Element. |
| [getStructureTextState](#getStructureTextState--) | Liest {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element. Wert: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Liest oder setzt den Hyperlink für das Link-Element. |
| [setText](#setText-java.lang.String-) | Fügt Textinhalt zum aktuellen Textelement hinzu. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Position anpassen.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

Liest oder setzt den Hyperlink für das Link-Element.

**Returns:**
Hyperlink-Instanz

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Liest {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element. Wert: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element.

**Returns:**
Wert: StructureTextState Objekt für das Textelement der Struktur.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Liest oder setzt den Hyperlink für das Link-Element.

### setText {#setText-java.lang.String-}
Fügt Textinhalt zum aktuellen Textelement hinzu.
